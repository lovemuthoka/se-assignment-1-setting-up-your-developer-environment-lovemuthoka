[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15299056&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
Check System Requirements:
Ensure that your PC meets the minimum system requirements for Windows 11. You can find these requirements on Microsoft's official website.

Download Windows 11:
Visit the official Microsoft website for downloading Windows 11. Here's the link: Microsoft Windows 11 Download.

Create Installation Media:
You have the option to download Windows 11 as an ISO file, which you can then use to create a bootable USB drive. Alternatively, if you're upgrading from an older version of Windows, you can use the Windows Update Assistant.

Install Windows 11:
Once you have created the installation media (USB drive or DVD), insert it into your PC and restart it. Follow the on-screen instructions to begin the installation process. Make sure to back up your important files before proceeding with the installation.

Activate Windows 11:
After installation, you'll need to activate Windows 11 with a valid product key. If you're upgrading from Windows 10, your digital license should automatically carry over.

Post-Installation Setup:
Complete the setup process by configuring your preferences, installing drivers, and updating Windows to ensure you have the latest features and security patches.
2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download Download VS Code:
Visit the official Visual Studio Code website to download the installer. Here's the link: Visual Studio Code Download.

Choose Your Platform:
VS Code is available for Windows, macOS, and Linux. Select the version appropriate for your operating system and click on the download button.

Run the Installer:
Once the download is complete, run the installer file (.exe for Windows, .dmg for macOS, or .deb/.rpm for Linux). Follow the installation wizard's instructions.

Open Visual Studio Code:
After installation, launch VS Code from your desktop or applications folder.

Install Extensions (Optional but Recommended):
VS Code supports extensions for various programming languages and functionalities. You can enhance its capabilities by installing extensions directly from the VS Code Marketplace. To access the Marketplace, click on the Extensions icon in the Activity Bar on the side of the window (or use the shortcut Ctrl+Shift+X).

Configure VS Code (Optional):
Customize VS Code to suit your preferences by modifying settings (File > Preferences > Settings or Ctrl+, on Windows/Linux, Cmd+, on macOS). You can change themes, keyboard shortcuts, and more.

Start Coding:
Once everything is set up, you can start coding by opening a folder or a file in VS Code and utilizing its features like IntelliSense, debugging tools, version control integration, and more.
3. Set Up Version Control System:Installing Git
Download Git:

Go to the official Git website: Git Downloads.
Download the installer for your operating system (Windows, macOS, Linux) and run it.
Follow Installation Instructions:

For Windows: Follow the steps in the installer. You can choose the default options unless you have specific preferences.
For macOS: Open the downloaded .dmg file and follow the installation instructions.
For Linux: Use your package manager to install Git. For example, on Ubuntu, you can use sudo apt-get install git.
Verify Installation:

Open a terminal (Command Prompt on Windows) and type git --version to verify that Git has been installed correctly.
Configuring Git
Set Up Your Identity:

Open a terminal (or Git Bash on Windows).
Set your username: git config --global user.name "Your Name"
Set your email address: git config --global user.email "your.email@example.com"
(Optional) Configure Editor:

If you prefer to use a text editor other than the default, configure it: git config --global core.editor "code --wait" (replace "code --wait" with your preferred editor command).
Creating a GitHub Account
Sign Up for GitHub:
Go to GitHub and sign up for a new account. Follow the instructions to complete the signup process.
Initializing a Git Repository and Making Your First Commit
Create a New Repository on GitHub:

Log in to your GitHub account.
Click on the "+" sign in the upper-right corner and select "New repository".
Give your repository a name, optionally add a description, choose public or private visibility, and click on "Create repository".
Initialize Git Repository Locally:

Open a terminal or Git Bash.
Navigate to the directory where you want to initialize your Git repository. For example: cd ~/Projects/my-project
Initialize Git in this directory: git init
Add Files and Make Your First Commit:

Create some files in your project directory or copy existing files into it.
Add the files to your Git repository staging area: git add . (this adds all files; replace . with specific file names to add individual files).
Commit the files to the repository: git commit -m "Initial commit" (replace "Initial commit" with a meaningful commit message describing your changes).
Link Local Repository to GitHub:

On your GitHub repository page, you should see a section "…or push an existing repository from the command line". Copy the commands under "…or push an existing repository from the command line" and paste them into your terminal or Git Bash.
Pushing Changes to GitHub:

After linking your local repository to GitHub, push your changes to GitHub: git push -u origin main (assuming your default branch is main; if it's master, use git push -u origin master).

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
Installing Python
Download Python:

Visit the official Python website: Python.org.
Navigate to the Downloads section.
Download the installer for Python. Choose the latest stable version suitable for your operating system (Windows, macOS, or Linux).
Run the Installer:

Once the download is complete, run the Python installer.
On Windows, ensure you check the box that says "Add Python to PATH" during the installation process. This will make it easier to run Python from the command prompt.
On macOS and Linux, the installer should guide you through the installation process. You might need administrative privileges.
Verify Installation:

Open a terminal or command prompt.
Type python --version (or python3 --version depending on your system) to verify that Python has been installed correctly.
Installing Necessary Tools
Text Editor or IDE (e.g., Visual Studio Code):

If you haven't installed an IDE yet, refer to the steps mentioned earlier to download and install Visual Studio Code or any other preferred IDE.
Package Manager (pip):

pip is Python's package installer and is usually installed automatically with Python. To check if pip is installed, type pip --version in your terminal or command prompt. If not installed, you can install it using the instructions on pip's installation page.
Additional Libraries and Packages:

Depending on your project requirements, you may need to install additional Python packages using pip. For example, if you're working with data science, you might want to install numpy, pandas, matplotlib, etc. Use pip install <package-name> to install these packages.
Set Up Python Environment (Optional)
Virtual Environments:
It's a good practice to use virtual environments to manage dependencies and isolate project environments. To create a virtual environment, use:
Copy code
python -m venv myenv
Replace myenv with your preferred name for the virtual environment. Activate the virtual environment:
On Windows:
Copy code
myenv\Scripts\activate
On macOS/Linux:
bash
Copy code
source myenv/bin/activate
Building and Executing Code
Write Your Python Code:

Use your preferred text editor or IDE to write Python code.
Run Python Code:

Save your Python files with a .py extension.
Open a terminal or command prompt, navigate to the directory containing your Python file, and run it using:
Copy code
python filename.py
Replace filename.py with your actual Python file name.
5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Check if pip is Installed:

Open a terminal or command prompt.
Type pip --version (or pip3 --version on some systems) and press Enter.
Install pip (if not already installed):

If pip is not installed or if you encounter an error indicating that pip is not recognized, you can install it using the following steps:
For Windows
Download get-pip.py:

Download get-pip.py script from https://bootstrap.pypa.io/get-pip.py.
Open Command Prompt:

Open a command prompt as Administrator.
Navigate to the Directory:

Navigate to the directory where you downloaded get-pip.py.
Install pip:

Run the following command:
arduino
Copy code
python get-pip.py
Verify Installation:

After installation, verify pip by running:
css
Copy code
pip --version
For macOS and Linux
Install pip using Package Manager:

For most Linux distributions and macOS, pip is usually installed with Python by default. However, if it's not installed, you can install it using your package manager.

For Debian/Ubuntu:

sql
Copy code
sudo apt update
sudo apt install python3-pip
For Fedora:

Copy code
sudo dnf install python3-pip
For macOS (using Homebrew):

Copy code
brew install python3
This will also install pip alongside Python.

Verify Installation:

After installation, verify pip by running:
css
Copy code
pip --version
Upgrading pip
If you already have pip installed but want to upgrade it to the latest version, you can use the following command:

Windows:

css
Copy code
python -m pip install --upgrade pip
macOS and Linux:

css
Copy code
pip install --upgrade pip
Using pip
Once pip is installed, you can use it to install Python packages. For example, to install a package like requests, you would use:

Copy code
pip install requests
6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html Download MySQL Installer:

Go to the official MySQL website: MySQL Installer.
Click on the "Download" button for the MySQL Installer appropriate for your Windows version (32-bit or 64-bit).
Run the MySQL Installer:

Once the installer is downloaded, run it by double-clicking on the downloaded file (mysql-installer-web-community-x.x.xx.x.msi).
MySQL Installer Setup:

The installer will guide you through the setup process. Click "Yes" if prompted by User Account Control.
Choose the setup type. For most cases, "Developer Default" or "Server Only" is sufficient. Click "Next".
Select Products:

In the MySQL Products screen, select the products you want to install. Typically, you'll need MySQL Server and optionally MySQL Workbench (a graphical tool for managing and interacting with MySQL databases).
Installation Process:

Proceed with the installation by clicking "Next" and then "Execute" to begin the installation process.
Follow the prompts to set up MySQL Server. You'll be asked to set a root password during the installation.
Complete the Installation:

Once the installation completes, click "Next" and then "Finish" to exit the installer.
Configure MySQL Server
Start MySQL Server:

MySQL Server might start automatically after installation. If not, you can manually start it:
Open the Start menu and search for "MySQL" to find and start "MySQL Command Line Client" or "MySQL 5.x Command Line Client".
Alternatively, open Windows Services (services.msc), find "MySQL" or "MySQL Server", and start it.
Connect to MySQL Server:

Open MySQL Command Line Client or MySQL Workbench (if installed).
Use the root user and the password you set during installation to connect to the MySQL server.
Create Databases and Users (Optional):

Once connected, you can create databases and users as needed using SQL commands. For example:
sql
Copy code
CREATE DATABASE mydatabase;
CREATE USER 'myuser'@'localhost' IDENTIFIED BY 'mypassword';
GRANT ALL PRIVILEGES ON mydatabase.* TO 'myuser'@'localhost';
FLUSH PRIVILEGES;
Verify Installation:

Verify that MySQL Server is running and you can connect to it using MySQL Workbench or the MySQL Command Line Client.
Additional Notes
Firewall Settings: MySQL Server may require incoming connections to be allowed through the firewall. If you encounter connection issues, ensure that MySQL is allowed through your firewall settings.

MySQL Workbench: MySQL Workbench is a useful graphical tool for managing MySQL databases. If you installed it during the MySQL Installer setup, you can use it to visually manage your databases, run queries, and more.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines. Installing Docker
Download Docker Desktop:

Visit the Docker website: Docker Desktop.
Download Docker Desktop for your operating system (Windows or macOS).
Install Docker Desktop:

Run the downloaded installer and follow the installation instructions.
On Windows, ensure to enable Hyper-V and Containers features if prompted during installation.
Verify Docker Installation:

After installation, Docker Desktop should be running. You should see the Docker icon in your system tray (Windows) or status bar (macOS).
Open a terminal (Command Prompt on Windows, Terminal on macOS) and type docker --version to verify that Docker is installed correctly.
Using Docker for Development Environments
Dockerfile:

Create a Dockerfile in your project directory to define your application environment. Here's a basic example for a Python project:

Dockerfile
Copy code
# Use an official Python runtime as a parent image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME World

# Run app.py when the container launches
CMD ["python", "app.py"]
Adjust the Python version (python:3.9-slim) and other details according to your project requirements.

Build the Docker Image:

Open a terminal or command prompt.
Navigate to your project directory containing the Dockerfile.
Build the Docker image using the following command:
perl
Copy code
docker build -t my-python-app .
Run the Docker Container:

Once the image is built, you can run a container based on this image:
arduino
Copy code
docker run -p 4000:80 my-python-app
This command runs the container and maps port 80 from the container to port 4000 on your host machine. Adjust ports as needed.
Accessing the Container:

You can access the running container using Docker commands like docker exec for executing commands inside the container.
Benefits of Using Docker
Isolation: Docker containers encapsulate dependencies and configurations, ensuring consistent behavior across different environments.
Portability: Docker images can be shared and deployed easily across different machines.
Version Control: Dockerfiles provide a version-controlled, reproducible way to define development environments.
Considerations
Learning Curve: Docker has a learning curve, especially for complex setups and orchestration.
Resource Consumption: Containers consume additional resources compared to lightweight virtual environments.
Integration: Docker integrates well with CI/CD pipelines and cloud platforms for deployment.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration. 
Visual Studio Code (VS Code) Extensions
Extensions Marketplace:

Open VS Code and go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side (or using the shortcut Ctrl+Shift+X).
In the Extensions Marketplace, you can search for and install extensions to enhance your coding environment.
Essential Extensions:

Language Support:

Python: Provides syntax highlighting, IntelliSense, and debugging support for Python.
JavaScript (ESLint, Prettier): Adds linting, formatting, and syntax highlighting for JavaScript and related frameworks.
Java: Offers support for Java development, including debugging and language features.
HTML/CSS: Enhances HTML and CSS editing with code completion and formatting.
Productivity Tools:

GitLens: Supercharges the Git capabilities built into VS Code with features like blame annotations, commit details, and more.
Bracket Pair Colorizer: Helps distinguish matching brackets with different colors for easier code navigation.
Live Share: Enables real-time collaborative editing and debugging across multiple users.
Themes and Visual Enhancements:

Material Theme: Offers a Material Design-inspired theme with vibrant colors and icons.
Dracula Official: Provides a dark theme with vibrant colors that's easy on the eyes during extended coding sessions.
Code Quality and Testing:

ESLint: Integrates ESLint for JavaScript and TypeScript linting.
Jest: Adds support for testing with Jest, including test result highlighting and code lenses.
Installation and Usage:

To install an extension, search for its name in the Extensions Marketplace, click on "Install", and then reload VS Code if prompted.
Configure extensions through their respective settings in VS Code. You can access these settings by clicking on the gear icon next to an installed extension in the Extensions view.
Customizing Your Development Environment
Keybindings: Customize keyboard shortcuts for faster navigation and actions using the Keyboard Shortcuts editor in VS Code (File > Preferences > Keyboard Shortcuts or Ctrl+K Ctrl+S).

Settings: Adjust VS Code settings (File > Preferences > Settings or Ctrl+,) to tailor the editor behavior, theme, and extensions to your preferences.

Keeping Extensions Updated
Automatic Updates: By default, VS Code checks for updates to installed extensions and updates them automatically. You can manage extension updates manually if needed.
Additional IDEs and Text Editors
If you're using other IDEs or text editors like IntelliJ IDEA, Atom, Sublime Text, or Emacs, each has its own ecosystem of plugins and extensions available through their respective package managers or plugin repositories. Explore their documentation or community forums to discover and install plugins tailored to your development needs.
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:Setting Up Your Developer Environment
Overview
This document provides a step-by-step guide to setting up a comprehensive developer environment on a Windows machine. The setup includes configuring tools such as Visual Studio Code, Python, Git, and Docker to facilitate software development.

Tools to Install
Visual Studio Code (VS Code)
Python
Git
Docker
Step 1: Installing Visual Studio Code (VS Code)
Download VS Code:

Visit the Visual Studio Code website and download the installer for Windows.
Run the downloaded installer and follow the installation instructions.
Ensure to add VS Code to the PATH during installation.
Install Extensions:

Open VS Code.
Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side (or use the shortcut Ctrl+Shift+X).
Install essential extensions like Python, GitLens, and Docker for VS Code.
Customize Settings:

Modify settings in VS Code (File > Preferences > Settings) according to personal preferences, including themes, keybindings, and editor configurations.
Step 2: Installing Python
Download Python:

Visit the Python website and download the latest version of Python for Windows.
Run the downloaded installer.
Select "Add Python to PATH" during installation.
Verify Python installation by opening a command prompt and typing python --version.
Install pip:

pip is included automatically with Python installations starting with Python 3.4. Verify by typing pip --version in the command prompt.
Step 3: Installing Git
Download Git:

Visit the Git website and download the installer for Windows.
Run the downloaded installer.
During installation, select appropriate options (e.g., adjusting PATH environment) and follow prompts.
Verify Git installation by opening a command prompt and typing git --version.
Configure Git:

Set up your username and email using:
arduino
Copy code
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Step 4: Installing Docker
Download Docker Desktop:

Visit the Docker website and download Docker Desktop for Windows.
Run the downloaded installer and follow the installation instructions.
Enable Hyper-V and Containers features if prompted.
Verify Docker Installation:

Docker Desktop should start automatically after installation.
Verify Docker installation by opening a command prompt and typing docker --version.
Run Docker Containers:

Use Docker CLI or Docker Compose to manage and run containers. Example:
arduino
Copy code
docker run -p 4000:80 my-python-app
Troubleshooting and Additional Customizations
Firewall Issues: If encountering connectivity issues with Docker, ensure Docker is allowed through the firewall.
Extension Compatibility: Check compatibility and updates for VS Code extensions regularly to avoid conflicts.
Performance Tuning: Adjust Docker resources (CPU, memory) in Docker Desktop settings based on system performance.
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
