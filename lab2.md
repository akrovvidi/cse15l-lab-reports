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

