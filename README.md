# 2020-PY-101

### Overview
This Python for beginners training course leads the students from the basics of writing and running Python scripts to more advanced features such as file operations, working with binary data, and using the extensive functionality of Python modules. Extra emphasis is placed on features unique to Python, such as tuples, array slices, and output formatting.

### Prerequisites
Students should already be comfortable using the operating system (Linux, Unix, Windows, Solaris, Mac OS X, etc.) on which they will be running Python. While not mandatory, basic skills with at least one other programming language are desirable.
### Materials
All Python training students will receive comprehensive courseware in GitHub.

### Software Needed on Each Student PC
* Any Windows 10, Linux, or Mac OS X operating system
* Python 3 or later
  ![](https://lh3.googleusercontent.com/-6W_a1QS8RfM/X1sv1nJAS5I/AAAAAAAAp3Q/Yg5jrQn32ZQMUZ_h9SIt23jmktMBlPlFwCK8BGAsYHg/s0/2020-09-11.png)
  * [64 bit](https://www.python.org/ftp/python/3.7.9/python-3.7.9-amd64.exe)
  * [32 bit](https://www.python.org/ftp/python/3.7.9/python-3.7.9-amd64-webinstall.exe)
  * [Download and Installation Instrucation]()
* An IDE with Python support (PyCharm Community Edition is an excellent free option, but there are several other good ones)
### Objectives
* Master the fundamentals of writing Python scripts
* Learn core Python scripting elements such as variables and flow control structures
* Discover how to work with lists and sequence data
* Write Python functions to facilitate code reuse
* Use Python to read and write files
* Make their code robust by handling errors and exceptions properly
* Work with the Python standard library
* Explore Python's object-oriented features
* Search text using regular expressions
### Course 
* [Introducation To Python Program ](https://github.com/reddyprasade/2020-PY-101/blob/master/PPT/Introduction%20to%20Python%20Programming.pdf)

### Registation Process 
* [Registation Link](https://forms.gle/iyT5kxrTZKRUT7n49)
* All Students them to join Before 15 minutes to the meeting Link
* Ask to mute 🔕 while explain
* Ask them if any one have question in session, we have discussion after Completing the training

### Meeting Link:
* [link](https://meet.google.com/ppp-feno-gqb)
* Join to Meeting 
  * ![Step-1](https://lh3.googleusercontent.com/-CzELC5wghnY/X19_jCahhqI/AAAAAAAAAHo/Cp3Dm7B2RVc6JxjRfNne1343LGOWNJrBwCK8BGAsYHg/s0/2020-09-14.png)
  * ![Step-2](https://lh3.googleusercontent.com/-vMOP_ZFncC4/X199gHWNnmI/AAAAAAAAp6I/dFSBb0WzVvAS6c00TKmAXkPFH536gfo_gCK8BGAsYHg/s0/2020-09-14.png)
  * ![Step-3](https://lh3.googleusercontent.com/-8ytudhew9w8/X19-itFNGWI/AAAAAAAAp6Q/EvzCtodZo88hqomUmY2N0XB9t4V8j9GrQCK8BGAsYHg/s0/2020-09-14.png)

***
### Installation Process
#### **Step 1:** Download the Python Installer binaries
1. Open the [official Python website](https://www.python.org/downloads/windows/)in your web browser. Navigate to the Downloads tab for Windows.
2. Choose the latest Python 3 release. In our example, we choose the latest Python 3.7.3 version.
3. Click on the link to download Windows x86 executable installer if you are using a 32-bit installer. In case your Windows installation is a 64-bit system, then download Windows x86-64 executable installer.
Download Python Installer

![](https://cdn.journaldev.com/wp-content/uploads/2019/06/DownloadRel.png)

#### **Step 2:** Run the Executable Installer
1. Once the installer is downloaded, run the Python installer.
2. Check the Install launcher for all users check box. Further, you may check the Add **Python 3.7** to path check box to include the interpreter in the execution path.
Customize Installation
![](https://cdn.journaldev.com/wp-content/uploads/2019/06/customize_installation.png)

3. Select Customize installation.
  
Choose the optional features by checking the following check boxes:

4. Documentation
5. pip
6. tcl/tk and IDLE (to install tkinter and IDLE)
7. Python test suite (to install the standard library test suite of Python)
8. Install the global launcher for `.py` files. This makes it easier to start Python
9. Install for all users.
Python Windows 10 Optional Features
![](https://cdn.journaldev.com/wp-content/uploads/2019/06/optional_features-1.png)

Click Next.

10. This takes you to Advanced Options available while installing Python. Here, select the Install for all users and Add Python to environment variables check boxes.
Optionally, you can select the Associate files with Python, Create shortcuts for installed applications and other advanced options. Make note of the python installation directory displayed in this step. You would need it for the next step.
![](https://cdn.journaldev.com/wp-content/uploads/2019/06/advanced_options.png)

After selecting the Advanced options, click Install to start installation.
![](https://cdn.journaldev.com/wp-content/uploads/2019/06/setup_successful.png)
Python Installer Advanced Options

11. Once the installation is over, you will see a Python Setup Successful window.
Python Windows 10 Setup Successful

#### **Step 3:** Add Python to environmental variables
The last (optional) step in the installation process is to add Python Path to the System Environment variables. This step is done to access Python through the command line. In case you have added Python to environment variables while setting the Advanced options during the installation procedure, you can avoid this step. Else, this step is done manually as follows.

In the Start menu, search for “advanced system settings”. Select “View advanced system settings”. In the “System Properties” window, click on the “Advanced” tab and then click on the “Environment Variables” button.

Locate the Python installation directory on your system. If you followed the steps exactly as above, python will be installed in below locations:


`C:\Program Files (x86)\Python37-32: for 32-bit installation`
`C:\Program Files\Python37-32: for 64-bit installation`

The folder name may be different from “Python37-32” if you installed a different version. Look for a folder whose name starts with Python.

Append the following entries to PATH variable as shown below:
![](https://cdn.journaldev.com/wp-content/uploads/2019/06/environmentalvar_to-path.png)

Adding Python Environmental variable To Path
![](https://cdn.journaldev.com/wp-content/uploads/2019/06/config_envvar_new-1.png)

Config Envvar New

#### **Step 4: Verify the Python Installation**

You have now successfully installed Python 3.7.3 on Windows 10. You can verify if the Python installation is successful either through the command line or through the IDLE app that gets installed along with the installation.

Search for the command prompt and type “python”. You can see that Python 3.7.3 is successfully installed.
![](https://cdn.journaldev.com/wp-content/uploads/2019/06/verify-python-cmdpromt.png)

Verify if Python is installed through the Command prompt

An alternate way to reach python is to search for “Python” in the start menu and clicking on IDLE (Python 3.7 64-bit). You can start coding in Python using the Integrated Development Environment(IDLE).
![](https://cdn.journaldev.com/wp-content/uploads/2019/06/verify-python-startmenu.png)

Verify if Python is installed using IDLE app

Hurray! You are ready to start developing Python applications in your Windows 10 system.


