[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282090&assignment_repo_type=AssignmentRepo)
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
Developer Environment Setup Documentation

 1. Operating System Installation
1. Download Windows 11 ISO:
   - Visit the [Microsoft Software Download](https://www.microsoft.com/software-download/windows11) page.
   - Select the Windows 11 ISO file to download.

2. Create Bootable USB:
   - Download and install [Rufus](https://rufus.ie/).
   - Insert a USB drive and use Rufus to create a bootable USB drive with the Windows 11 ISO.

3. Install Windows 11:
   - Insert the bootable USB into your computer and restart.
   - Enter BIOS/UEFI settings (usually by pressing F2, F12, Delete, or Esc during boot).
   - Set the USB as the first boot device.
   - Follow the on-screen instructions to install Windows 11.





 


2. IDE Installation


 Installation of Visual Studio Code

1. Download VS Code:
   - Visit the [Visual Studio Code website](https://code.visualstudio.com/) and download the installer for Windows.

2. Install VS Code:
   - Run the installer and follow the installation prompts.
   - Select additional tasks such as creating a desktop icon and adding to PATH.

3. Initial Configuration:
   - Open VS Code and go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.

4. Explore Extensions and Plugins:
   - Python: Provides rich support for Python.
     - Search for "Python" and click Install.
   - Pylint: A linter for Python.
     - Search for "Pylint" and click Install.
   - Prettier: A code formatter.
     - Search for "Prettier - Code formatter" and click Install.
   - GitLens: Supercharges the Git capabilities built into VS Code.
     - Search for "GitLens" and click Install.
   - Visual Studio IntelliCode: AI-assisted development.
     - Search for "Visual Studio IntelliCode" and click Install
 
3. Version Control Setup

Installation of Git and GitHub Account Setup

1. Download and Install Git:
   - Visit the [Git website](https://git-scm.com/) and download the installer for Windows.

2. Install Git:
   - Run the installer and follow the installation prompts.
   - Configure your Git installation (e.g., setting the default editor).

3. Create a GitHub Account:
   - Visit [GitHub](https://github.com/join) and sign up for a new account.

4. First Commit:
   - Create a new repository on GitHub.
   - Clone the repository to your local machine:
     ```sh
     git clone https://github.com/yourusername/your-repository.git
     ```
   - Navigate to the repository directory and create a new file (e.g., README.md).
   - Stage, commit, and push the file:
     ```sh
     git add README.md
     git commit -m "Initial commit"
     git push origin main
     ```





4. Programming Languages and Runtimes

Steps for Installing Python:

Installation of Python and Package Managers

1. Download and Install Python:
   - Visit the [Python website](https://www.python.org/downloads/) and download the latest version for Windows.

2. Install Python:
   - Run the installer and ensure you check "Add Python to PATH".
   - Follow the installation prompts.

3. Verify Installation:
   - Open Command Prompt and check the Python and pip installation:
     ```sh
     python --version
     pip --version

   


   

6. Database Configuration

Steps for Installing MySQL:

1. Download MySQL:
   - Visit the [MySQL website](https://dev.mysql.com/downloads/installer/) and download the MySQL Installer for Windows.

2. Install MySQL:
   - Run the installer and follow the installation prompts.
   - Choose "Server Only" or "Developer Default" as per your requirement.
   - Configure the MySQL server (e.g., setting the root password).

3. Verify Installation:
   - Open MySQL Workbench and connect to the MySQL server.



7. Development Environments and Virtualization (Optional)

Optional Steps for Installing and Setting Up Docker:

1. Download Docker:
   - Visit the Docker Desktop download page: [Docker Download](https://www.docker.com/products/docker-desktop).
   - Download and run the Docker Desktop installer.

   ![Docker Download](images/docker-download.png)

2. Installation Process:
   - Follow the installation instructions.
   - Start Docker Desktop and follow the setup wizard.


3. Verify Installation:
   - Open Command Prompt or PowerShell and type:
 	```bash
 	docker --version
 	```


8. Extensions and Plugins

List of Installed Extensions for VS Code:

1. Install Extensions:
   - Open VS Code.
   - Go to the Extensions view (`Ctrl+Shift+X`).
   - Search for and install the following extensions:
 	- Python
 	- GitLens — Git supercharged
 	- Docker
 	- Prettier - Code formatter
 	- ESLint
 	- MySQL

  
9. Challenges and Solutions

1. Challenge: Installing MySQL and Configuring the Root Password
   - Solution: Followed a step-by-step tutorial and used the official MySQL documentation for troubleshooting.

2. Challenge: Initializing a Git Repository and Making the First Commit
   - Solution: Used Git documentation and GitHub guides to understand the commands and workflow.

3. Compatibility Issues:
   - Some software may not support the latest version of Windows or have compatibility issues.




Reflection


Setting up a developer environment can be complex, but breaking down the process into manageable steps and utilizing official documentation greatly simplifies it. The main challenges were compatibility and configuration issues, which were addressed by careful attention to detail and use of community resources.

This document serves as a comprehensive guide for setting up a developer environment on Windows , ensuring a smooth and efficient development process.




Developer Environment Setup Documentation

 1. Operating System Installation
1. Download Windows 11 ISO:
   - Visit the [Microsoft Software Download](https://www.microsoft.com/software-download/windows11) page.
   - Select the Windows 11 ISO file to download.

2. Create Bootable USB:
   - Download and install [Rufus](https://rufus.ie/).
   - Insert a USB drive and use Rufus to create a bootable USB drive with the Windows 11 ISO.

3. Install Windows 11:
   - Insert the bootable USB into your computer and restart.
   - Enter BIOS/UEFI settings (usually by pressing F2, F12, Delete, or Esc during boot).
   - Set the USB as the first boot device.
   - Follow the on-screen instructions to install Windows 11.





 


2. IDE Installation


 Installation of Visual Studio Code

1. Download VS Code:
   - Visit the [Visual Studio Code website](https://code.visualstudio.com/) and download the installer for Windows.

2. Install VS Code:
   - Run the installer and follow the installation prompts.
   - Select additional tasks such as creating a desktop icon and adding to PATH.

3. Initial Configuration:
   - Open VS Code and go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window.

4. Explore Extensions and Plugins:
   - Python: Provides rich support for Python.
     - Search for "Python" and click Install.
   - Pylint: A linter for Python.
     - Search for "Pylint" and click Install.
   - Prettier: A code formatter.
     - Search for "Prettier - Code formatter" and click Install.
   - GitLens: Supercharges the Git capabilities built into VS Code.
     - Search for "GitLens" and click Install.
   - Visual Studio IntelliCode: AI-assisted development.
     - Search for "Visual Studio IntelliCode" and click Install
 
3. Version Control Setup

Installation of Git and GitHub Account Setup

1. Download and Install Git:
   - Visit the [Git website](https://git-scm.com/) and download the installer for Windows.

2. Install Git:
   - Run the installer and follow the installation prompts.
   - Configure your Git installation (e.g., setting the default editor).

3. Create a GitHub Account:
   - Visit [GitHub](https://github.com/join) and sign up for a new account.

4. First Commit:
   - Create a new repository on GitHub.
   - Clone the repository to your local machine:
     ```sh
     git clone https://github.com/yourusername/your-repository.git
     ```
   - Navigate to the repository directory and create a new file (e.g., README.md).
   - Stage, commit, and push the file:
     ```sh
     git add README.md
     git commit -m "Initial commit"
     git push origin main
     ```





4. Programming Languages and Runtimes

Steps for Installing Python:

Installation of Python and Package Managers

1. Download and Install Python:
   - Visit the [Python website](https://www.python.org/downloads/) and download the latest version for Windows.

2. Install Python:
   - Run the installer and ensure you check "Add Python to PATH".
   - Follow the installation prompts.

3. Verify Installation:
   - Open Command Prompt and check the Python and pip installation:
     ```sh
     python --version
     pip --version

   


   

6. Database Configuration

Steps for Installing MySQL:

1. Download MySQL:
   - Visit the [MySQL website](https://dev.mysql.com/downloads/installer/) and download the MySQL Installer for Windows.

2. Install MySQL:
   - Run the installer and follow the installation prompts.
   - Choose "Server Only" or "Developer Default" as per your requirement.
   - Configure the MySQL server (e.g., setting the root password).

3. Verify Installation:
   - Open MySQL Workbench and connect to the MySQL server.



7. Development Environments and Virtualization (Optional)

Optional Steps for Installing and Setting Up Docker:

1. Download Docker:
   - Visit the Docker Desktop download page: [Docker Download](https://www.docker.com/products/docker-desktop).
   - Download and run the Docker Desktop installer.

   ![Docker Download](images/docker-download.png)

2. Installation Process:
   - Follow the installation instructions.
   - Start Docker Desktop and follow the setup wizard.


3. Verify Installation:
   - Open Command Prompt or PowerShell and type:
 	```bash
 	docker --version
 	```


8. Extensions and Plugins

List of Installed Extensions for VS Code:

1. Install Extensions:
   - Open VS Code.
   - Go to the Extensions view (`Ctrl+Shift+X`).
   - Search for and install the following extensions:
 	- Python
 	- GitLens — Git supercharged
 	- Docker
 	- Prettier - Code formatter
 	- ESLint
 	- MySQL

  
9. Challenges and Solutions

1. Challenge: Installing MySQL and Configuring the Root Password
   - Solution: Followed a step-by-step tutorial and used the official MySQL documentation for troubleshooting.

2. Challenge: Initializing a Git Repository and Making the First Commit
   - Solution: Used Git documentation and GitHub guides to understand the commands and workflow.

3. Compatibility Issues:
   - Some software may not support the latest version of Windows or have compatibility issues.




Reflection


Setting up a developer environment can be complex, but breaking down the process into manageable steps and utilizing official documentation greatly simplifies it. The main challenges were compatibility and configuration issues, which were addressed by careful attention to detail and use of community resources.

This document serves as a comprehensive guide for setting up a developer environment on Windows , ensuring a smooth and efficient development process.




