# *Lab Report 1*




# Installing VS Code
I have not included a tutorial for this stage, as I had actually installed it last quarter. However, once you are able to install VS Code, your home screen should look something like this.

<img width="1291" alt="VSCode" src="https://user-images.githubusercontent.com/122575272/212447856-06349fce-fc54-435e-87b2-5e5195724a29.png">




# Accessing your CSE15L Account
To access your specific account for CSE15L, simply click on the link below and login using your credentials:


[CSE15L Access Page](https://sdacs.ucsd.edu/~icc/index.php)


Once you can login and find your CSE15L username, you will have to reset your password if you don't have one already. To reset, access the global password change website by clicking the link below


[Global Password Reset](https://sdacs.ucsd.edu/~icc/password.php)


If you want to change the password only for your cse15L account and not for your triton link, then type none in place of your student ID.
Once you've set up your account, it's time to move on to the next step!

# Remote Connection

Now that we've successfully set up our account, it's time we connect to the remote servers in the CSE Basement! The first thing we want to do is open VSCode. Once we open VSCode, click on "Terminal" and then "New Terminal". Once you see the terminal open up, paste the following code below onto your terminal. It's just "ssh [your cse15L username]@ieng6.ucsd.edu".


<img width="554" alt="SSH_" src="https://user-images.githubusercontent.com/122575272/212447510-fbbb662f-5a22-4e65-adaf-f41df3201249.png">


Once you've done that and successfully and entered your password, the terminal will print the following welcome statement, as seen above.

# Trying some commands

We can try running some commands on the remote server using the terminal in VS Code. To make it easier, I have listed some of the commands you can use below and their significance.


* cd - Used to change the current directory to the path provided
* pwd - Short for print working directory, displays the current working directory
* ls - Used to list the contents of the provided path
* cat - Prints the contents of one or more provided paths

Hopefully, you now understand what each of those commands means so that you can start running these commands in the terminal. Below you can see some sample commands I used on the remote server.


<img width="312" alt="RunCommands" src="https://user-images.githubusercontent.com/122575272/212448564-0db1f9e2-223d-43c4-a10c-db4993f2f715.png">

As you can see, pwd just printed the current working directory and then when I ran “ls”, it just printed the contents of the root file, which is “perl5”. These are just one of the many commands you can use in the terminal.


