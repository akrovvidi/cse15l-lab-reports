# *Lab Report 1*

# Part 1

The code for StringServer can be seen below:

```
import java.io.IOException;
import java.net.URI;
import java.util.ArrayList;

 class StringServerHandler implements URLHandler{
    ArrayList<String> messagesList = new ArrayList<String>();
    public String handleRequest(URI url) {
        if (url.getPath().equals("/add-message")){
            String[] messages = url.getQuery().split("=");
            messagesList.add(messages[1]);
            return String.join("\n",messagesList);
        }
        return "404 Not Found!";
    }
}
class StringServer {
    public static void main(String[] args) throws IOException {
        if(args.length == 0){
            System.out.println("Missing port number! Try any number between 1024 to 49151");
            return;
        }
        int port = Integer.parseInt(args[0]);
        Server.start(port, new StringServerHandler());
    }
}
```

In this screenshot, the methods that are called are StringServer and the StringServerHandler. The StringServer class is called to generate the port number and a working website to run the commands. The StringServerHandler method is called to handle requests and check for any "add-message" queries. The valid argument for the StringServerHandler method would be a valid url of type URI. 


<img width="639" alt="messageEquals1" src="https://user-images.githubusercontent.com/122575272/215026711-1eeacdb3-db6e-4473-a785-43fadc4fda73.png">

In this second screenshot, I changed the add-message to "How are you" which makes the web server print the previous and current messages. Similar to the previous screenshot, the methods called are StringServer and StringServerHandler. However, in this case, the ArrayList for messagesList is updated with another element to hold the String object and print it out. 



<img width="635" alt="messageEquals2" src="https://user-images.githubusercontent.com/122575272/215026768-2b9baa18-6029-47c3-94ac-2c42feac3ac0.png">


# Part 2

The bug I chose for this part of the lab is the one in method reversed which returns a new array with all the elements in the input array reversed. 

## Failure-inducing input:
The failure inducing input for this code is the integer array - {5,4,3,2,1}
The code which tests the method using this input can be seen below:
```
  @Test
  public void manualTestReversed(){
    int input[] = {5,4,3,2,1};
    ArrayExamples.reversed(input);
    assertArrayEquals(new int[]{1,2,3,4,5}, input);
  }
  ```
  
## Success-inducing input:
  An input that does not induce a failure for the reversed method is the integer array - {0,0,0}
  ```
  @Test
  public void manualTestReversed(){
    int input[] = {0,0,0};
    ArrayExamples.reversed(input);
    assertArrayEquals(new int[]{0,0,0}, input);
  }
  }
  ```
  
## The symptoms
  
  The screenshot below shows the symptom caused by the bug in the program which results in the failed test
  
  
  
  <img width="610" alt="TestReversedFailed" src="https://user-images.githubusercontent.com/122575272/215035184-b59f91a2-b7e6-44e4-b192-808d5ec25c7b.png">
  
  
  
  This screenshot shows the test passing despite a bug in the program
  
  
<img width="586" alt="TestReversedSuccess" src="https://user-images.githubusercontent.com/122575272/215298904-6d2893b1-2b28-4544-83ce-40f6f007873e.png">

  
## Before fixing the bug:
  The code with the bug can be seen below:
   ```
  static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      arr[i] = newArray[arr.length - i - 1];
    }
    return arr;
  }
  ```
The problem with this code is that it copies from an empty array which causes all indices to be 0. Also, instead of returning the new Array, this method returns the input array.
  
## After fixing the bug:
   ```
  static int[] reversed(int[] arr) {
    int[] newArray = new int[arr.length];
    for(int i = 0; i < arr.length; i += 1) {
      newArray[i] = arr[arr.length - i - 1];
    }
    return newArray;
  }
  ```
  
  The following changes: `newArray[i] = arr[arr.length - i - 1];` and `return newArray;` allows the method to now work in its intended manner.

# Part 3

The new concept I learned from the last labs is understanding the meaning of symptoms and bugs while also being able to identify them in methods. I understood that symptom is related to the actual behavior of the program, while bugs are the failures/flaws in the program that causes those particular symptoms. In addition, I learned how to implement web servers like StringServer and perform specific actions on them. 
