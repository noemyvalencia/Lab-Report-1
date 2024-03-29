# Introduction to connecting remotely into your course-specific account!
---
To do so, follow the 3 basic steps down below:

## Step 1: Install Visual Studio Code

If you haven't installed VSCode to your computer, do the following:

1. Click the [Link](https://code.visualstudio.com/download) and follow the steps according to your computer system.
2. After doing so, your Visual Studio Code should look something like this:
![Image](Screenshot%202023-04-06%20at%202.13.01%20PM.png)

## Step 2: Connect Remotely:

1. Now that you have VSCode, go ahead and open a new terminal, if you're using MacOS it should look like the following picture:
![Image](Screenshot%202023-04-06%20at%202.16.36%20PM.png)

2. Select the option bash from your terminal like in the picture:
![Image](Screenshot%202023-04-06%20at%202.19.17%20PM.png)

3. In your terminal type the command `ssh cs15lsp23zz@ieng6.ucsd.edu` where the zz is replaced by the letters in your own username.
4. It will ask you for permission, so make sure to type `yes` and hit enter.
5. After saying yes, it will ask you for your password, **Note that you will not see any characters when typing your password, DO NOT WORRY,** type it as usual and finish your log in, it should look like the following picture:
![Image](Screenshot%202023-04-06%20at%202.35.59%20PM.png)
6. THAT'S IT! You now have remote access to your account on ieng6.

## Step 3: Make sure it's running well:

Now that you have remote access, you want to make sure that you are connected correctly, to do that, run the following commands:
* pwd: returns full path name of your working directory.
* cd: changes current working directory.
* ls -lat: returns contents of the current directory. One per line, starting with "." and in chronological order starting from newest.
* ls -a: returns contents of the current directory starting with ".".
* ls <directory>: where <directory> is replaced by /home/linux/ieng6/cs15lsp23/cs15lsp23abc and "abc" is your username.
* cd ~: changes current working directory to previous.
* cat /home/linux/ieng6/cs15lsp23/public/hello.txt
* cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/

* **Note that the commands might look something like this:**
* pwd
![Image](Screenshot%202023-04-06%20at%202.47.25%20PM.png)
* cd
![Image](Screenshot 2023-04-23 at 5.12.46 PM.png)
  
* ls -lat
![Image](Screenshot 2023-04-23 at 5.14.01 PM.png)
  
* ls -a
![Image](Screenshot 2023-04-23 at 5.14.23 PM.png)
  
* ls <directory>
<img width="610" alt="Screenshot 2023-04-23 at 5 05 49 PM" src="https://user-images.githubusercontent.com/130100414/234080386-61e6df54-4784-4c28-9441-adb40708a7dd.png">
  
* cd ~
![Image](Screenshot 2023-04-23 at 5.16.08 PM.png)
  
* cat
![Image](Screenshot 2023-04-23 at 5.08.58 PM.png)
  
* cp
![Image](Screenshot 2023-04-23 at 5.12.12 PM.png)

---
If you followed the steps accordingly, you should now have remote access to your ieng6 account!

