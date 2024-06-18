[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281439&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.

ANSWERS ASSIGMENT 1 WEEK 2 SOFTWARE DEVELOPMENT:
TASK 1
Step-by-step instructions
-Visit the Windows 11 download page:https://www.microsoft.com/software-download/windows11

Open your web browser and go to the Windows 11 download page.
Download Windows 11 Installation Tutorial:

On the download page, click the "Download Now" button under the "Windows 11 Installation Assistant" section.
Save the downloaded file (Windows11InstallationAssistant.exe) to your computer.

-Use the installation wizard:

Locate the downloaded file and double-click it to run the Windows 11 Installation Assistant.
Follow the on-screen instructions to perform the installation.

-Check out the program requirements:

The Installation Assistant will verify that your system meets the minimum requirements for Windows 11. If your system is compatible, you will see the message "Your PC is compatible."
If your system does not meet the requirements, you will be prompted for an error message and possible solutions.
 

-Backup your data:
Before performing the installation, make sure you have backed up all important data and files. Use external hard drives, cloud storage, or other storage options.
Start the installation:

Click the "Accept and install" button to start the installation process.
The installation wizard downloads the necessary files and prepares your PC for the upgrade.

-Reboot and install:
Once the files have been downloaded and repaired, you will be prompted to restart your PC.
Restart your system and click "Restart now" to start installing Windows 11 .

-Complete Installation:
After rebooting, the Windows 11 installation process will continue. Your PC will restart several times during the process.
Follow any additional on-screen instructions to complete the process, such as setting up your region, configuring your keyboard, creating or signing up for a Microsoft account

TASK 2
 -Visit the Official Website of the Visual Studio Code using any web browser like Google Chrome, Microsoft Edge, etc.  

 - Press the “Download for Windows” button on the website to start the download of the Visual Studio Code Application.

 -When the download finishes, then the Visual Studio Code Icon appears in the downloads folder. 

 -Click on the Installer icon to start the installation process of the Visual Studio Code.

 -After the Installer opens, it will ask you to accept the terms and conditions of the Visual Studio Code. Click on I accept the agreement and then click the Next button. 


 -Choose the location data for running the Visual Studio Code. It will then ask you to browse the location. Then click on the Next button. 

 -Then it will ask to begin the installation setup. Click on the Install button.

-After clicking on Install, it will take about 1 minute to install the Visual Studio Code on your device.
-After the Installati on setup for Visual Studio Code is finished, it will show a window like this below. Tick the “Launch Visual Studio Code” checkbox and then click Next.

-After the previous step, the Visual Studio Code window opens successfully 

TASK 3

-Download and Install Git:
Visit the Git download page.https://git-scm.com/download 
Select the appropriate version for your OS and download it.
Run the installer and follow the setup instructions, ensuring you select options such as "Git from the command line" and "Use Visual Studio Code as Git’s default editor."

-Configure Git:
Open a terminal or command prompt.
Run the following commands to set your username and email:
$git config --global user.name "Your Name"
$git config --global user.email "your-email@example.com"

-Create a GitHub Account:
Visit GitHub and sign up for a new account if you don’t have one.
Verify your email address to activate the account.

-Initialize a Git Repository:
Create a new repository on GitHub by clicking on the "New" button.
Name your repository and choose its visibility (public or private).
Initialize the repository with a README file (optional).

Clone and Commit:
Clone the repository to your local machine:
$git clone https://github.com/your-username/my-project.git
$cd my-project

Add a new file and make your first commit:
$echo "# My Project" > README.md
$git add README.md
$git commit -m "Initial commit"
$git push -u origin main/master

TASK 4
-Select Python Version

Deciding on a version depends on what you want to do in Python. The two major versions are Python 2 and Python 3. Choosing one over the other might be better depending on your project details. If there are no constraints, choose whichever one you prefer.
-Download Python Executable Installer
Start by downloading the Python executable installer for Windows:
Open a web browser and navigate to the Downloads for Windows section of the official Python website.
Locate the desired Python version. 
 Click the link to download the file. Choose either the Windows 32-bit or 64-bit installer.(The download is approximately 25MB.)

-Run Executable Installer
The steps below guide you through the installation process:

1.Run the downloaded Python Installer.

2.The installation window shows two checkboxes:

Admin privileges. The parameter controls whether to install Python for the current or all system users. This option allows you to change the installation folder for Python.
Add Python to PATH. The second option places the executable in the PATH variable after installation. You can also add Python to the PATH environment variable manually later. 
For the most straightforward installation, we recommend ticking both checkboxes.

3. Select the Install Now option for the recommended installation (in that case, skip the next two steps).

To adjust the default installation options, choose Customize installation instead and proceed to the following step.
The default installation installs Python to C:\Users\[user]\AppData\Local\Programs\Python\Python[version] for the current user. It includes IDLE (the default Python editor), the PIP package manager, and additional documentation. The installer also creates necessary shortcuts and file associations.

Customizing the installation allows changing these installation options and parameters.

4. Choose the optional installation features. Python works without these features, but adding them improves the program's usability. 
Click Next to proceed to the Advanced Options screen.

5. The second part of customizing the installation includes advanced options.

Choose whether to install Python for all users. The option changes the install location to C:\Program Files\Python[version]. If selecting the location manually, a common choice is C:\Python[version] because it avoids spaces in the path, and all users can access it. Due to administrative rights, both paths may cause issues during package installation.

Other advanced options include creating shortcuts, file associations, and adding Python to PATH. 
After picking the appropriate options, click Install to start the installation.

6. Select whether to disable the path length limit. Choosing this option will allow Python to bypass the 260-character MAX_PATH limit. 

-Add Python to Path (Optional)
If the Python installer does not include the Add Python to PATH checkbox or you have not selected that option, continue in this step. Otherwise, skip to the next step.

Adding the Python path to the PATH variable alleviates the need to use the full path to access the Python program in the command line. It instructs Windows to review all the folders added to the PATH environment variable and to look for the python.exe program in those folders.

To add Python to PATH, do the following:

1. In the Start menu, search for Environment Variables and press Enter. 
2. Click Environment Variables to open the overview screen.
3. Double-click Path on the list to edit it.
Alternatively, select the variable and click the Edit button.

4. Double-click the first empty field and paste the Python installation folder path.




 

Alternatively, click the New button instead and paste the path.

5. Click OK to save the changes. If the command prompt is open, restart it for the following step.

-Verify Python Was Installed on Windows
The first way to verify that Python was installed successfully is through the command line. Open the command prompt and run the following command:
$python --version

TASK 5
 Install Package Managers(: Install pip for Python.)

 -Verify pip Installation:
Pip comes bundled with Python 3.4 and later versions.
Open a terminal or command prompt.
Run the following command to check if pip is installed:
$pip --version
 

$python -m pip install --upgrade pip

TASK 6:
-Download MySQL
The simplest and recommended method is to download MySQL Installer for Windows from https://dev.mysql.com/downloads/installer/ and execute it.

-Select mysql-installer-web-community-8.0.23.msi if you have good internet connection, otherwise choose mysql-installer-community-8.0.23.msi.

Install MySQL
After downloading, unzip it, and double click the MSI installer .exe file. 

Then follow the steps below:

1. "Choosing a Setup Type" screen: Choose "Full" setup type. This installs all MySQL products and features. Then click the "Next" button to continue.

2. "Check Requirements" screen: The installer checks if your pc has the requirements needed. If there is some failing requirements, click on each item to try to resolve them by clicking on the Execute button that will install all requirements automatically. Click "Next".

3. "Installation" screen: See what products that will be installed. Click "Execute" to download and install the Products. After finishing the installation, click "Next".

4. "Product Configuration" screen: See what products that will be configured. Click the "MySQL Server 8.0.23" option to configure the MySQL Server. Click the "Next" button. Choose the "Standalone MySQL Server/Classic MySQL Replication" option and click on the "Next" button. In page  "Type and Networking" set Config Type to "Development Computer" and "Connectivity" to "TCP/IP" and "Port" to "3006". Then, click the "Next" button.

5. "Authentication Method" screen: Choose "Use Strong Password Encryption for Authentication". Click "Next".

6. "Accounts and Roles" screen: Set a password for the root account. Click "Next".

7. "Windows Service" screen: Here, you configure the Windows Service to start the server. Keep the default setup, then click "Next".

8. "Apply Configuration" screen: Click the "Execute" button to apply the Server configuration. After finishing, click the "Finish" button.

9. "Product Configuration" screen: See that the Product Configuration is completed. Keep the default setting and click on the "Next" and "Finish" button to complete the MySQL package installation.

10. In the next screen, you can choose to configure the Router. Click on "Next", "Finish" and then click the "Next" button.

11. "Connect To Server" screen: Type in the root password (from step 6). Click the "Check" button to check if the connection is successful or not. Click on the "Next" button.

12. "Apply Configuration" screen: Select the options and click the "Execute" button. After finishing, click the "Finish" button.

13. "Installation Complete" screen: The installation is complete. Click the "Finish" button.

-Verify MySQL Installation
Open the MySQL Command Line Client from cmd.

You should see a mysql> prompt. If you have set any password, write your password here.

Now, you are connected to the MySQL server, and you can execute all the SQL command at mysql.

TASK 7
-Download Docker:
 

Visit the Docker download page.
Download Docker Desktop for your OS.
Install Docker:

-Run the downloaded installer.
Follow the installation instructions, agreeing to the license terms and enabling necessary features.
Verify Docker Installation:

-Open a terminal or command prompt.
Run the following command to check Docker version:
$docker --version

-Start Using Docker:
Pull and run a sample image
$docker run hello-world
This command downloads a test image and runs it in a container, verifying your Docker installation.

TASK 8
-Open Visual Studio Code:

-Launch Visual Studio Code.
Install Extensions:

-Click on the Extensions icon in the Activity Bar on the side of the window.
Search for popular extensions like Python, GitLens, Prettier, and much more 
Click "Install" to add the desired extensions to your IDE.
Configure Extensions:

-Go to File > Preferences > Settings to configure the installed extensions according to your workflow.
