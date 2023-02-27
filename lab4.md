# *Lab Report 4*

In this lab, I will be going through steps 4-8 of the competition.

# Task 4 - SSH

This task focused on logging onto the remote servers using the ssh command. However, one of the downsides of using `ssh`  as we all know is that it keeps asking us to enter the password everytime we log in. Therefore, in an effort to save time, I ran the `ssh-keygen` command on my terminal. Once i ran the command, I followed the following steps:
*  Pressed `<enter>` until you see a random pattern printed on the terminal
*  I then entered my password for the final time

After that I ran the ssh command shown below to log in to the remote server

```
ssh cs15lwi23atr@ieng6.ucsd.edu
```
Once I typed that, I am no longer required to enter the password which would eventually save me considerable time. This is how it looks like after I ran the command:


# Task 5 - Cloning the forked repository

To clone a fork of the repository, I ran the following command on my terminal:



```
git clone https://github.com/akrovvidi/lab7
```

Executing the command above and then pressing `<enter>`, printed the following lines onto my terminal.


# Task 6 - Running the Tests

*NOTE*

Before executing the following task, it is important not to forget to `cd lab7`. 

Since these test files run on JUnit, we can't just compile these files using `javac`. So to first import JUnit, I  went to the week3 section of the lab and used the `Ctrl-C` and `Ctrl-V` commands for copying and pasting the command  `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` onto my terminal. Then, I repeated the same process for the command  `<java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests>`. After I ran these commands, the message displayed on the terminal can be seen below which should state that one of the tests failed. 

# Task 7 - Fixing the code

In order to examine the code present in ListExamples.java, we first have to run the following command:
```
nano ListExamples.java
```

Executing this command pulls up the following on the terminal:



This opens a text editor in our terminal which allows us to examine and change to code so that it passes the testers. I amended by changing `index1 +=1` to `index2 +=1`. After that, I pressed `<Ctrl-X>` and then when it asks for confirmation I typed Y and then hit `<enter>` to exit out of the text editor.


# Task 8 - Running the tests

Now, in order to ensure these new changes pass the testers succesfuly, we have to compile and execute the tests again. Now, we obviously want to avoid the strain of copying and pasting those commands again. Therfore I just pressed the following keys: `<up><up><up><enter>` which executed `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` and then pressed the keys: `<up><up><up><up><enter>` which executed `<java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests>`. This then printed the following onto my terminal which shows that these changes passed both testers. 

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


