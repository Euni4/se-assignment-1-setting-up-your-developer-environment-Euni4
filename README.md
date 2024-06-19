[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283896&assignment_repo_type=AssignmentRepo)
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

# Download the Installer:

  Open your web browser and go to the official Visual Studio Code website: Visual Studio Code.
  Click on the Download for Windows button. This will download the installer for the latest stable version of VS Code.

# Run the Installer:

  Once the download is complete, locate the downloaded file (it should be named something like VSCodeSetup-x64-<version>.exe) in your Downloads folder or the location where your browser saves downloaded files.
  Double-click on the installer file to run it.

# Setup Wizard:

  The Visual Studio Code Setup Wizard will open. Click Next to continue.

# Accept the License Agreement:

  Read the license agreement, then check the box that says "I accept the agreement" and click Next.

# Select Installation Location:

  Choose the destination folder where you want to install VS Code. The default location is usually fine for most users. Click Next to continue.

# Select Additional Tasks:

  You will be presented with a list of additional tasks. Here are the recommended options:
  Create a desktop icon: Check this box if you want a shortcut on your desktop.
  Add "Open with Code" action to Windows Explorer file context menu: Check this box to add an option to open files with VS Code directly from the right-click menu.
  Add "Open with Code" action to Windows Explorer directory context menu: Check this box to add an option to open folders with VS Code directly from the right-click menu.
  Register Code as an editor for supported file types: This option will associate VS Code with common file types.
  Add to PATH: This option will allow you to open VS Code from the command line.
  After selecting the desired options, click Next.

# Install:

  Click the Install button to begin the installation process. The setup wizard will copy the necessary files to your computer.

# Launch VS Code:

  Once the installation is complete, you will see a final setup screen. Check the box that says "Launch Visual Studio Code" and click Finish.
  Post-Installation Steps:
  Update VS Code:

  After launching VS Code, it's a good idea to check for updates. Click on the gear icon in the bottom left corner, select Check for Updates, and follow any prompts to install updates.
  Install Extensions:

  VS Code is highly customizable with extensions. To install extensions, click on the Extensions icon on the left sidebar or press Ctrl+Shift+X.
  Search for extensions you need, such as Python, JavaScript, GitLens, etc., and click Install.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

# Install Git on Windows
  Download Git:

  Go to the official Git website: Git for Windows.
  Click on Download to get the latest version of the Git installer.

  Run the Installer:

  Locate the downloaded file (e.g., Git-<version>-64-bit.exe) in your Downloads folder or where your browser saves downloaded files.
  Double-click the installer to run it.

  Follow the Installation Steps:

  Click Next to start the setup.

  Keep the default installation location unless you have a specific directory where you want to install Git. Click Next.
  Select the components you want to install. The default options are usually fine. Click Next.
  Choose the default editor used by Git. You can leave it as Vim or select another editor like Notepad++ if you prefer.    Click Next.
  Adjust your PATH environment. Select "Git from the command line and also from 3rd-party software." Click Next.
  Continue clicking Next for the remaining default settings until you reach the Install button.
  Click Install to begin the installation process.
  Once the installation is complete, click Finish.

# Configure git

- Open Git bash:
  After installation, open git bash from the start menu or the desktop shortcut.

- Set your username:
  git config --global user.name "your name"

- set your email:
  git config --global user.rmail "your email"

- verify configuration:
  git config --list:
  this will show the configurations you set and other git settings.

# Create a Git hub Account

  Go to Github
  sign up for an account 
  verify your email and account, from the link sent by Github

# Initiaize a git repository for you project

- Create a new project folder:
  Navigate to the directory where you want to create your project and create it: 
  cd:f/
  mkdir project1
  cd project 1
  Run git init to create a new git repository in tha directory
- Add and commit changes:
  Add your project files to the repository using: 
  git add project1
  Commit your changes with descriptive message:
  git commit -m "project number 1"

# Connect to GitHub:

  Create a GitHub account if you haven’t already.
  On GitHub, create a new repository for your project.
  Link your local Git repository to the remote GitHub repository using git remote add origin <repository_url>.



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Open your preferred web browser (Chrome, Firefox, Edge, etc.).
  Go to the Official Python Website:

- Navigate to the official Python website: https://www.python.org/.
  Download the Python Installer:

-On the homepage, hover over the Downloads tab and click on Windows.
  Click on the big yellow button that says Download Python 3.x.x (where 3.x.x is the latest version).
  Step 2: Run the Python Installer
  Locate the Installer:

- Once the download is complete, locate the downloaded file in your Downloads folder or the location where your browser saves downloaded files. The file should be named something like python-3.x.x.exe.
  Run the Installer:

- Double-click the installer file to run it. A dialog will appear asking if you want to allow this app to make changes to your device. Click Yes.
  Step 3: Customize Installation
  Customize Installation Options:

- On the first screen of the installer, check the box that says Add Python 3.x to PATH at the bottom. This ensures      that you can use Python from the command line.
  Click Customize installation to choose optional features and install locations.
  Optional Features:

# Ensure that all optional features are checked. These typically include:
  Documentation
  pip
  tcl/tk and IDLE
  Python test suite
  py launcher
  Click Next.
  Advanced Options:

  On the Advanced Options screen, you can choose to install Python for all users, which requires administrator  privileges.  Other options can be left at their default settings.
  Select the installation directory if you want to change it, but the default location is usually fine.
  Click Install.
Step 4: Complete Installation
  Wait for Installation to Complete:
  The installer will now install Python. This might take a few minutes.
  Once the installation is complete, you will see a screen saying "Setup was successful." Click Close.
  Step 5: Verify Installation
  Open Command Prompt:

  Press Win + R, type cmd, and press Enter to open the Command Prompt.
  Verify Python Installation:

  In the Command Prompt, type the following command and press Enter:

python --version
  This should display the version of Python you just installed, confirming that the installation was successful.
  Verify pip Installation:

  Also, verify that pip (Python's package installer) is installed by typing the following command and pressing Enter:



5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Install pip on your system if you don't have it already. You can download get-pip.py and run python get-pip.py, or use your system's package manager (e.g. sudo apt install python3-pip for Ubuntu).
   Navigate to the project's directory and create a requirements.txt file that lists the packages you need.
   Run pip install -r requirements.txt to install all the packages from the file. You can also use pip install to install a single package.
   



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Go to the MySQL Download Page:

   Open your web browser and go to the MySQL download page: MySQL Installer.
   Choose the Installer:

   Select the Windows (x86, 32-bit), MSI Installer if you have a 32-bit system, or the Windows (x86, 64-bit), MSI Installer for a 64-bit system.
   Click the Download button.
   Install MySQL
   Run the Installer:

   Once the download is complete, navigate to your Downloads folder and double-click the installer file to run it.
   Choose Setup Type:

   In the MySQL Installer, choose the Setup Type that best suits your needs. For a typical installation, select Developer Default. If you want to customize the components to install, select Custom.
   Check Requirements:

  The installer will check for any missing requirements. If anything is missing, the installer will prompt you to install them.

  Install MySQL:

  Click Execute to download and install the required components. This process may take some time.

  Configure MySQL
  Begin Configuration:

  Once the installation is complete, the MySQL Installer will start the configuration process automatically. Click Next to begin.

  High Availability:

  Choose Standalone MySQL Server / Classic MySQL Replication and click Next.
  Type and Networking:

  For Config Type, select Development Machine.
  Ensure TCP/IP is enabled and set the port to 3306. Make sure to check Open Windows Firewall port for network access.
  Click Next.

  Authentication Method:

  Choose Use Strong Password Encryption for Authentication (RECOMMENDED) and click Next.
  Set Root Password:

  Enter and confirm a strong password for the root user. Make sure to remember this password as you'll need it later.
  Optionally, you can add other users by clicking Add User. Click Next.

  Windows Service:

  Ensure Configure MySQL Server as a Windows Service is checked.
  Set the service name to MySQL57.
  Select Standard System Account and click Next.
  Apply Configuration:

  Click Execute to apply the configuration settings. This process may take a few moments.
  Once completed, click Finish.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Syntax Highlighting:

  Python
  JavaScript (ES6) Code Snippets
  HTML CSS Support

  Linting:

  ESLint
  Pylint
  Stylelint

  Code Formatting:

  Prettier - Code formatter
  Beautify

  Version Control:

  GitLens
  Git History




9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

  Table of Contents

  Install Python
  Install pip
  Install Extensions (e.g., matplotlib)
  Custom Configurations and Customizations
  Troubleshooting

  Download Python:

  Download the latest version of Python for Windows.

  Run the Installer:

  Execute the downloaded installer.
  Important: Check the box that says "Add Python to PATH".
  Select "Install Now" for a standard installation.

  Verify Installation:

  Open Command Prompt (press Win + R, type cmd, and press Enter).
  Run the command: python --version
  when the latest version of python is displayed the installation was successfull.

  Install pip
  Download get-pip.py:

  Open your web browser and download get-pip.py from this link.
  Run get-pip.py:

  Open Command Prompt and navigate to the directory where get-pip.py is saved (e.g., cd Downloads).

  Run the command: python get-pip.py
  This will install pip.
  Verify pip Installation:

  Run the command: pip --version
  This will display the latest version of pip installed, that will be a confirmation of a successfull installation.

  Install Extensions (e.g., matplotlib)
  Open Command Prompt:

  Install matplotlib:

  Run the command:

  pip install matplotlib
  Verify matplotlib Installation:

  Open a Python interactive shell by typing python in the Command Prompt.
  Run the following commands to check if matplotlib is installed:
  python

  import matplotlib
  print(matplotlib.__version__)
  You should see the installed version of matplotlib.

  # Custom Configurations and Customizations
  
  Python Environment Configuration
  Environment Variables:
  Ensure that the Python executable and Scripts directory are added to the PATH environment variable. This was done during the installation by checking the "Add Python to PATH" box.
  
  IDE/Editor Configuration
  Visual Studio Code Extensions:

  Python Extension: Provides rich support for Python including features like IntelliSense, linting, and debugging.
  code --install-extension ms-python.python

  Customization in VS Code:

  Settings: Customize settings for better readability and functionality

  # Troubleshooting
  
  Common Issues and Fixes
  Python Command Not Found:

  Issue: The command python is not recognized.
 
  Solution: Edited system environment variables by adding Python  to the PATH environment variable manually.

  pip Command Not Found:


  Issue: The command pip is not recognized.
 
  Solution: Checked pip is installed correctly by running get-pip.py with Python. Verify pip is in the Scripts directory within the Python installation directory, and that this directory is in the PATH.
  
  Permission Errors:

  Issue: Permission errors when installing packages.
  
  Solution: Run Command Prompt as an administrator and used the --user flag with pip to install packages in the user directory.


  pip install --user packageName
  matplotlib Import Error:

  Issue: Import error when trying to use matplotlib.
  
  Solution: Checked matplotlib is installed correctly by running pip install matplotlib. Verified the Python environment is being used by my IDE/editor and matches the one where matplotlib is installed.
  
#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
# Done at the top
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
# https://github.com/Euni4/Pythonproject.git

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
