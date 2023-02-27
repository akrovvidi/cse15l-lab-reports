# *Lab Report 4*

In this lab, I will be going through steps 4-9 of the competition.

# Task 4 - SSH

This task focused on logging onto the remote servers using the ssh command. However, one of the downsides of using `ssh`  as we all know is that it keeps asking us to enter the password everytime we log in. Therefore, in an effort to save time, I ran the `ssh-keygen` command on my terminal. Once i ran the command, I followed the following steps:
*  Pressed `<enter>` until you see a random pattern printed on the terminal
*  I then entered my password for the final time

After that I ran the ssh command shown below to log in to the remote server

```
ssh cs15lwi23atr@ieng6.ucsd.edu
```
Once I typed that, I am no longer required to enter the password which would eventually save me considerable time. This is how it looks like after I ran the command:

<img width="969" alt="Screenshot 2023-02-26 at 9 21 28 PM" src="https://user-images.githubusercontent.com/122575272/221482335-6732611b-9de7-49a5-8eda-2f4d721b6799.png">


# Task 5 - Cloning the forked repository

To clone a fork of the repository, I ran the following command on my terminal:



```
git clone https://github.com/akrovvidi/lab7
```

Executing the command above and then pressing `<enter>`, printed the following lines onto my terminal.


<img width="545" alt="Screenshot 2023-02-26 at 9 23 11 PM" src="https://user-images.githubusercontent.com/122575272/221482426-13fa0268-9d62-45e1-938d-ac469cfe7f67.png">



# Task 6 - Running the Tests

*NOTE*

Before executing the following task, it is important not to forget to `cd lab7`. 

Since these test files run on JUnit, we can't just compile these files using `javac`. So to first import JUnit, I  went to the week3 section of the lab and used the `Ctrl-C` and `Ctrl-V` commands for copying and pasting the command  `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` onto my terminal. Then, I repeated the same process for the command  `<java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests>`. After I ran these commands, the message displayed on the terminal can be seen below which should state that one of the tests failed.

<img width="967" alt="Screenshot 2023-02-26 at 9 23 34 PM" src="https://user-images.githubusercontent.com/122575272/221482575-914d2e00-1060-4ee4-a30a-aa9bf996ca46.png">

# Task 7 - Fixing the code

In order to examine the code present in ListExamples.java, we first have to run the following command:
```
nano ListExamples.java
```

Executing this command pulls up the following on the terminal:

<img width="936" alt="Screenshot 2023-02-26 at 7 55 25 PM" src="https://user-images.githubusercontent.com/122575272/221482688-d3351098-c949-4b06-a7cc-c7134d7693be.png">


This opens a text editor in our terminal which allows us to examine and change to code so that it passes the testers. I amended by changing `index1 +=1` to `index2 +=1`. After that, I pressed `<Ctrl-X>` and then when it asks for confirmation I typed Y and then hit `<enter>` to exit out of the text editor.


# Task 8 - Running the tests

Now, in order to ensure these new changes pass the testers succesfuly, we have to compile and execute the tests again. Now, we obviously want to avoid the strain of copying and pasting those commands again. Therfore I just pressed the following keys: `<up><up><up><enter>` which executed `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` and then pressed the keys: `<up><up><up><up><enter>` which executed `<java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests>`. This then printed the following onto my terminal which shows that these changes passed both testers. 


<img width="990" alt="Screenshot 2023-02-26 at 9 24 16 PM" src="https://user-images.githubusercontent.com/122575272/221482783-839db799-4815-4206-a9d1-f67ed16b2f8e.png">



# Task 9 - Pushing these changes

To push and commit these changes onto my git accound, I typed the following commands:

```
git add ListExamples.java ListExamplesTests.class
```
```
git commit -m "Changed"
```
```
git push git@github.com:akrovvidi/lab7.git
```

The `-m` refers to the message that is shown after commiting these changes. The message can be anything that effectively communicates its purpose. In this case, I used "Changed". After running these commands, the following can be seen in the terminal:

<img width="738" alt="Screenshot 2023-02-26 at 10 25 01 PM" src="https://user-images.githubusercontent.com/122575272/221490145-94e55665-33d5-4e01-8dcf-455d1f539748.png">


