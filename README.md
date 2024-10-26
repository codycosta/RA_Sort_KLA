# 5XX RA Sort Python script

### Turn a cluttered directory into a well organized file storage, ready for excel!

<h3 style='color:salmon'>
    <p>Please read if you are new to using python or need assistance with setting up your machine</p>
    <p>
        Setup should not take more than 20 minutes and is a one time deal, after that there's no other prerequisites to begin use. I've tried to make this guide as easy and beginner friendly as possible
    </p>
</h3>

<br>
<br>

# Usage

### Step 1:
Navigate to a folder where you have some RA files located\
For example let's say they exist in the following folder:

<code>cd ~/Documents/5XX/SV_RA</code>

### Step 2:

Run RA-sort.py:\
After downloading RA-sort.py from github here, I'd recommend keeping it (or a copy) close to, or even inside, the RA directory you intend to sort.\
This way, typing out the file path is not a hassle

<code>~/Documents/5XX/52XX/SV_RA> python [path to RA-sort.py]</code>

<br>

## Example
In the below photos you can see I have some RA files stored in:
### ~/KLA-RA-scripts/sample-RAs/
<br>

and my copy of RA-sort.py stored in the previous folder:
### ~/KLA-RA-scripts/
<br>

Keeping RA-sort.py close to the RA folder makes execution easy.\
I just need to navigate to my RA folder (samlple-RAs) and call on RA-sort.py which is in the previous folder:\
<br>

When running, you can use the **python** or **py** prefix command\
![image](readme-imgs/cmd.png)
<br>
<br>

### Before
![image](readme-imgs/cluttered-folder.png)
<br>
<br>

### After
![image](readme-imgs/cleaned-2.png)
<br>
<br>
<br>

# How To Download RA-sort.py
At the top of the page if you are reading this, click on RA-sort.py\
![image](readme-imgs/file.png)
<br>

Next, on the top right of the file page, click the button to download raw file\
![image](readme-imgs/download.png)
<br>

### That's it, your file will be in your downloads folder
<br>
<br>

# Priming Your Machine For Python
## Step 1: Make sure you have python installed (version 3.7 or later)
Python can be downloaded from https://www.python.org/. I would recommend installing the latest version if you are unsure.\
To check if your machine already has a version of python installed, simply press the windows key and search for 'python':\
![image](readme-imgs/check-python.png)
<br>
<br>
If you do not see a version installed, follow the instructions on Python's website linked above for a fresh install. After downloading, be sure to run the .exe file to install it.

<br>

## Step 2: Adding Python to your system path
This step will take the most work, but is not difficult to do.\
First, keep your path to python handy, we will need it later.\
<br>

You can find this located at: 
### C:\Users\USER\AppData\Local\Programs\Python\Python312\
Just enter your USER name and substitute Python312 with whichever version you downloaded.\
Python 3.13 is the latest release at the time of development.\
<br>

Next, press the windows key and type out 'env', and click on **Edit the system environment variables**
![image](readme-imgs/sys-env.png)
<br>
<br>

A new 'System Properties' window will open, and we want to click on **Environment Variables**\
![image](readme-imgs/sys-props.png)
<br>
<br>

This will bring up a new window called 'Environment Variables'\
Navigate to the **system variables** section and click on the item labeled Path and then click **Edit**
![image](readme-imgs/env-vars.png)
<br>
<br>

Another new window will pop up, and we will then click on **New**\
In the field that pops up, here is where you will paste in your PYTHON PATH from earlier\
You can see mine listed at the bottom\
![image](readme-imgs/edit-vars.png)
<br>

#### Go ahead and click on **OK** on all the open windows to close them, and you are done with path setup!

<br>

## Step 3:  Diasabling Execution Aliasing
This part is easier than step 2.\
Press the windows key and search for 'app exec', and click on **Manage app execution aliases**
![image](readme-imgs/execution.png)
<br>
<br>

Scroll down until you see 2 programs named **App Installer** with python.exe and python3.exe listed below the titles.\
Turn both of these **OFF**\
![image](readme-imgs/alias-off.png)
<br>
<br>


### Setup is finished, your computer is ready to run Python
### Navigate back to the top to read about the file Usage
