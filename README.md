[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15286503&assignment_repo_type=AssignmentRepo)
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

   First i visited the official website for visual studio code  https://code.visualstudio.com/
   Once on the website there was a prominent download button for all operating systems and I selected the one for windows since that is the OS that i use.
   The download took less than a minute to complete then I located the downloaded installer file that was in my downloads folder.
   I double-clicked on the installer file and the installation process started.
   A setup wizard was launched and i followed the on-screen instruction to proceed with the installation.
   I was required to choose a destination folder where i want to install the vs code and i left it on default location.
   I then selected the additional tasks and i selected the options based on my preferrence.
   I clicked on the 'finish' icon to complete the installation process.
   After the installation was complete, i launched vs code by finding it on my start menu.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Installing and Configuring git

   Go to the official Git website: https://git-scm.com/.
Click on the download link appropriate for your operating system for mine it is windows.
Once the download completes, locate the downloaded .exe file mine was in the downloads folder.
Double-click the installer file to start the installation.
Follow the prompts in the installer and accept the default settings.
Git Bash, a command-line terminal for Git, will also be installed along with Git.
After installing, I opened git bash by right clicking and i run as an administrator.
After that i set my git username ; 'git config --global user.name Wacuka Ngugi'
Then I set my git Email Address; 'git config --global user.email bossgirlwacuka@gmail.com'
I then verified if git has been installed correctly and is properly configured; 'git --version': Checks the Git version installed. 'git config --list': Lists all Git configurations.
And like that i finished my installation and configuration.

Creating a GitHub account

Visit the GitHub Website:
Open your web browser and go to https://github.com/.
On the GitHub homepage, you'll see a form to sign up for GitHub. Fill in the following details:
Username: 
Email Address: 
Password:
After filling in, Click on the "Sign up for GitHub" button.
I completed CAPTCHA verification to confirm that i was not a robot by following the instructions on the screen.
After signing up, GitHub sent a verification email to the email address I provided during registration.
I verified my account by filling in the code they sent and my account was created.

Initializing a git repository

Choose or create a directory on your local machine where you want to initialize the Git repository. You can do this using your operating system's file manager.
Navigate to the directory you created using your terminal, cd C:\Users\YourUsername\Desktop\your-project-directory
Once you are inside your project directory, initialize a new Git repository by running the following command: 'git init'
Create some files in your project directory.

Making your first commit

Add Files to the Staging Area
Use the git add command to add your files to the staging area; git add .
Once your files are staged, commit them to the Git repository with a descriptive commit message using the git commit command; 'git commit -m'


4. Install Necessary Programming Languages and Runtimes:Install Python  programming language from http://wwww.python.org required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  
Installing Python

Visit the official Python website at https://www.python.org/downloads/.
Download the installer appropriate for your operating system mine is for windows.
Choose the latest stable version of Python currently it is python 3.12.
Double-click the downloaded .exe file.
Check the box that says "Add Python 3.12 to PATH"
Click "Install Now" and follow the prompts to complete the installation.
After installation, open and check that Python is installed correctly by running: python --version.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Download the get-pip.py script; curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
   Execute the script to install pip:python get-pip.py
   After installation, verify that pip is installed correctly by checking its version: pip --version

6. Configure a Database (MySQL):
   Download and install MySQL database.https://dev.mysql.com/downloads/windows/installer/5.7.html
   
   Go to the https://dev.mysql.com/downloads/windows/installer/5.7.html website on your browser.
    My screen displayed an option to select version and operating system and i left it as is since it was the latest version and on windows OS.
    I clicked on download and waited for the process to finish.
    My screen then displayed 'MySQL Community downloads but i skiped the page and continued with my download.
    Open the downloaded installer file.
Choose the setup type.
Follow the prompts to install MySQL Server and other components you need.
Configure the MySQL Server. You will be prompted to set up the server, including specifying the root password and other settings.
Choose to start the MySQL Server automatically.
Complete the installation process and start MySQL Workbench to connect to your MySQL Server.
After installing MySQL, you can verify the installation by logging into the MySQL shell:mysql -u root -p
Enter the root password you set during the installation process. You should see the MySQL prompt:mysql>
You can use tools like MySQL Workbench or any other database management tools to connect to your MySQL server. For MySQL Workbench:

Open MySQL Workbench.
Create a new connection.
Enter the connection details (hostname, username, password).
Test the connection and connect to your database.


      
7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
    
    I use visual studio code as my text editor
    Syntax Highlighting:
       Python
       JavaScript
       HTML/CSS

   Linting:
      ESLint for JavaScript
      Pylint for Python 

   Code Formatting:
      Prettier for multiple languages
      Beautify for HTML, CSS, and JS

   Version Control Integration:
        GitLens for Git supercharged
        GitHub Pull Requests and Issues for GitHub integration

   Additional Useful Extensions:
       Live Server for a local development server with live reload feature for static & dynamic pages
       Debugger for Chrome to debug JavaScript code in the Google Chrome browser
       Docker to manage Docker containers and images

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
