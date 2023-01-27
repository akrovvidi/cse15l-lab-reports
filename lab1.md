# *Lab Report 1*




# Installing VS Code
I had actually installed it last quarter but to install VS Code, you will first have to visit the link below:


[VS Code Download](https://code.visualstudio.com/)


Once you're on the page, you will need to either "Download for macOS" or "Download for Windows," depending on your operating system. After installing it, your homepage should look similar to the one below.

<img width="1291" alt="VSCode" src="https://user-images.githubusercontent.com/122575272/212447856-06349fce-fc54-435e-87b2-5e5195724a29.png">


# Accessing your CSE15L Account
To access your specific account for CSE15L, simply click on the link below and login using your credentials:


[CSE15L Access Page](https://sdacs.ucsd.edu/~icc/index.php)


Once you can login and find your CSE15L username, you will have to reset your password if you don't have one already. To reset, access the global password change website by clicking the link below:


[Global Password Reset](https://sdacs.ucsd.edu/~icc/password.php)


If you want to change the password only for your cse15L account and not for your triton link, then type none in place of your student ID.
Once you've set up your account, it's time to move on to the next step!

# Remote Connection

Now that we've successfully set up our account, it's time we connect to the remote servers in the CSE Basement! The first thing we want to do is open VSCode. Once we open VSCode, click on "Terminal" which will be located in the top left hand corner if you are using a mac and then hit "New Terminal". Once you see the terminal open up, paste the following code below onto your terminal. It should go like this:

```
ssh [your cse15L username]@ieng6.ucsd.edu.
```

<img width="554" alt="SSH_" src="https://user-images.githubusercontent.com/122575272/215010737-f362874f-e83e-4fc4-b84e-76c33c822f99.png">



Once you've done that and successfully and entered your password, the terminal will print the following welcome statement, as seen above. However, if you're like and just reset your password, you will want to wait for about 15 minutes before you try logging in as chances are that your new password will not be recognized by the systems just yet.

# Trying some commands

We can try running some commands on the remote server using the terminal in VS Code. To make it easier, I have listed some of the commands you can use below and their significance.


```
* cd - Used to change the current directory to the path provided
* pwd - Short for print working directory, displays the current working directory
* ls - Used to list the contents of the provided path
* cat - Prints the contents of one or more provided paths
```

Hopefully, you now understand what each of those commands means so that you can start running these commands in the terminal. Below you can see some sample commands I used on the remote server.

<img width="312" alt="RunCommands" src="https://user-images.githubusercontent.com/122575272/215010911-98ea72e3-1aaa-4793-9900-84b806ec54b3.png">


As you can see, pwd just printed the current working directory and then when I ran “ls”, it just printed the contents of the root file, which is “perl5”. These are just one of the many commands you can use in the terminal.
