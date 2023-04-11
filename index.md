# Introduction to connecting remotely into your course-specific account!
---
To do so, follow the 3 basic steps down below:

## Step 1: Install Visual Studio Code

If you haven't installed VSCode to your computer, do the following:

1. Click the [Link](https://code.visualstudio.com/download) and follow the steps according to your computer system.
2. After doing so, your Visual Studio Code should look something like this:
![Image](https://github.com/noemyvalencia/Lab-Report-1/blob/main/Screenshot%202023-04-06%20at%202.13.01%20PM.png)

## Step 2: Connect Remotely:

1. Now that you have VSCode, go ahead and open a new terminal, if you're using MacOS it should look like the following picture:
![Image](https://github.com/noemyvalencia/cse15l-lab-reports/blob/main/Screenshot%202023-04-06%20at%202.16.36%20PM.png)

2. Select the option bash from your terminal like in the picture:
![Image](https://github.com/noemyvalencia/cse15l-lab-reports/blob/main/Screenshot%202023-04-06%20at%202.19.17%20PM.png)

3. In your terminal type the command `ssh cs15lsp23zz@ieng6.ucsd.edu` where the zz is replaced by the letters in your own username.
4. It will ask you for permission, so make sure to type `yes` and hit enter.
5. After saying yes, it will ask you for your password, **Note that you will not see any characters when typing your password, DO NOT WORRY,** type it as usual and finish your log in, it should look like the following picture:
![Image](https://github.com/noemyvalencia/cse15l-lab-reports/blob/main/Screenshot%202023-04-06%20at%202.35.59%20PM.png)
6. THAT'S IT! You now have remote access to your account on ieng6.

## Step 3: Make sure it's running well:

Now that you have remote access, you want to make sure that you are connected correctly, to do that, run the following commands:
* pwd
* cd
* ls -lat
* ls -a
* cd ~
**Note that the pwd command might look something like this:**
![Image](https://github.com/noemyvalencia/cse15l-lab-reports/blob/main/Screenshot%202023-04-06%20at%202.47.25%20PM.png)

---
If you followed the steps accordingly, you should now have remote access to your ieng6 account!

