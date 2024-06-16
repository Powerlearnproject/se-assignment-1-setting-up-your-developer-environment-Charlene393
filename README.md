[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283185&assignment_repo_type=AssignmentRepo)
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
    Sure, here's the documentation in the first person:

---

## My Developer Environment Setup Documentation

### 1. Download and Install Windows 11

1. Visit the Windows 11 Download Page:
   I went to [Windows 11 Download](https://www.microsoft.com/software-download/windows11).
   
2. Download Windows 11:
   I clicked on the 'Download now' button to get the Windows 11 Installation Assistant.
   
3. Install Windows 11:
   I ran the downloaded file and followed the on-screen instructions to install Windows 11 on my machine.

### 2. Install a Text Editor or Integrated Development Environment (IDE)

1. *isit the Visual Studio Code Download Page:
   I went to [Visual Studio Code Download](https://code.visualstudio.com/Download).

2. Download Visual Studio Code:
   I chose the version suitable for Windows.

3. Install Visual Studio Code:
   I ran the downloaded installer and followed the installation wizard to complete the setup.

### 3. Set Up Version Control System

#### Install Git

1. Visit the Git Download Page:
   I went to [Git Download](https://git-scm.com/download/win).

2. Download Git:
   I clicked on the download link for Windows.

3. Install Git:
   I ran the installer and followed the default settings.

#### Configure Git

1. Open Git Bash:
   I opened Git Bash from the Start menu.

2. Set My Username:
   ```bash
   git config --global Charlene393
   ```

3. Set My Email:
   ```bash
   git config --global Charlene.Mbugua@strathmore.edu
   ```

#### Create a GitHub Account

1. Visit GitHub:
   I went to [GitHub](https://github.com).

2. Sign Up:
   I created a new account by providing the required details.

#### Initialize a Git Repository

1. **Create a New Repository on GitHub:**
   - I clicked on the 'New' button on my GitHub dashboard.
   - I filled in the repository name and description.
   - I chose the visibility (public or private) and clicked 'Create repository'.

2. Clone the Repository:
   ```bash
   git clone https://github.com/Powerlearnproject/se-assignment-1-setting-up-your-developer-environment-Charlene393.git
   ```

3. Navigate to the Repository Directory:
   ```bash
   cd D:\plp\software engineering\ASSIGNMENTS
   ```

4. Make My First Commit:
   - I created a new file, e.g., `README.md`.
   - I added some initial content to the file.
   - I staged and committed the changes:
     ```bash
     git add README.md
     git commit -m "assignment 2"
     git push origin main
     ```

### 4. Install Necessary Programming Languages and Runtimes

#### Install Python

1. Visit the Python Download Page:
   I went to [Python Download](https://www.python.org/downloads/).

2. Download Python:
   I chose the latest version of Python suitable for Windows.

3. Install Python:
   I ran the installer and made sure to check the option "Add Python to PATH". I followed the installation steps.

### 5. Install Package Managers

#### Install pip

- Pip is included by default with Python installations from Python.org. To verify, I opened Command Prompt and typed:
  ```bash
  pip --version
  ```

### 6. Configure a Database (MySQL)

1. Visit the MySQL Download Page:
   I went to [MySQL Installer Download](https://dev.mysql.com/downloads/windows/installer/5.7.html).

2. Download MySQL Installer:
   I chose the web installer or the full installer.

3.Install MySQL:
   I ran the installer and followed the setup wizard to install MySQL. I chose the default settings.

### 7. Set Up Development Environments and Virtualization (Optional)

#### Consider Using Docker

1. Visit the Docker Download Page:
   I went to [Docker Desktop](https://www.docker.com/products/docker-desktop).

2. Download Docker Desktop:
   I chose the version for Windows.

3. Install Docker Desktop:
   I ran the installer and followed the instructions to complete the installation.

### 8. Explore Extensions and Plugins

#### Visual Studio Code Extensions

1. Open Visual Studio Code.

2. Install Extensions:
   - I went to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or pressing `Ctrl+Shift+X`.
   - I searched for and installed extensions such as:
     - Python
     - GitLens
     - Prettier - Code formatter
     - Docker

### 9. Document My Setup

I created a document outlining the steps taken:

---

## My Developer Environment Setup Documentation

Operating System:
- Windows 11

Text Editor/IDE:
- Visual Studio Code

Version Control System:
- Git
- GitHub Account: Charlene393

Programming Languages and Runtimes:
- Python

Package Managers:
- Pip (Python)
Database:
- MySQL

Development Environments and Virtualization:
- Docker (optional)

Extensions and Plugins:
- Visual Studio Code Extensions:
  - Python
  - GitLens
  - Prettier - Code formatter
  - Docker

Additional Configurations:
- Git configuration with Charlene393 and Charlene.Mbugua@strathmore.edu.
- First Git commit and push to GitHub.

---

By following these steps and documenting my process, I have a comprehensive guide to setting up my developer environment. If I encounter any specific issues or need further assistance, I will refer back to this documentation.



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
