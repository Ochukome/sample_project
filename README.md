
 Setting Up a Development Environment

1. Selecting an operating system,  Windows 10 home was selected as my preferred operating system that suits my preference and project requirement.

2. Install a Text Editor or Integrated Development Environment (IDE)

 Action Performed
Downloaded and installed Visual Studio Code from the website given (https://code.visualstudio.com/Download).

 Documentation
Visual Studio Code is a powerful, cross-platform code editor developed by Microsoft. It offers a rich set of features, including syntax highlighting, code completion, debugging, and built-in Git integration. Visual Studio Code is highly extensible, allowing developers to install additional extensions and customize their development environment.

Challenges:
- I experienced Performance issues because my machine was older or less powerful.


3. Set Up Version Control System

 Action Performed
- Installed Git on the local machine.
- Created a GitHub account for hosting repositories.
- Initialized a Git repository for the project and made the first commit. (https://github.com/Ochukome/sample_project)

 Documentation
Git is a widely-used distributed version control system that allows developers to track changes in their codebase, collaborate with others, and manage different versions of their projects. GitHub is a popular web-based hosting service for Git repositories, providing a platform for collaborative development, code review, and issue tracking.

i was able to set up git using this steps :

- Download and install Git from the official website (https://git-scm.com/downloads).
-  Open a terminal or command prompt and run the following command to configure your Git username and email:
   
   git config --global user.name "Your Name"
   git config --global user.email "your@email.com"
   
- Create a new GitHub account or log in to your existing account at https://github.com.

- initialize a new Git repository by running the following command:
  
   git init
  
- Add all your project files to the staging area using:
   
   git add .

- Commit your changes with a descriptive message using:
   
   git commit -m "Initial commit"
   
- Create a new repository on GitHub using the GUI from (github.com)

Challenges:
- i had Difficulty understanding Git concepts and commands

3. Install Necessary Programming Languages and Runtimes

 Action Performed
Installed Python from https://www.python.org, as it was the required programming language for the project.

 Documentation
Python is a versatile and widely-used programming language known for its simplicity, readability, and extensive ecosystem of libraries and frameworks. To install Python on your machine, follow these steps:

1. Visit the official Python website (https://www.python.org/downloads/) and download the latest version of Python for your operating system.
2. Run the installer and follow the on-screen instructions.
3. Verify the installation by opening a terminal or command prompt and running the following command:
  
   python --version
  
   This should display the installed version of Python.

Challenges:
- i had issues running some scripts because i didnt add python to PATH while installing
- Setting up the correct environment variables for Python

 4. Install Package Managers

 Action Performed
Installed the pip package manager for Python.

 Documentation
Package managers are tools that simplify the process of installing, upgrading, and managing third-party libraries and dependencies for a particular programming language. For Python, the most widely-used package manager is pip (Python Package Installer).

To install pip on your machine, follow these steps:

- Open a terminal or command prompt.
- Run the following command to install pip:
  
   python -m ensurepip --default-pip
   
- Verify the installation by running:
   
   pip --version
   
   This should display the installed version of pip.

Once pip is installed, you can use it to install Python packages and libraries by running the following command:


pip install <package_name>




 5. Configure a Database (MySQL)

 Action Performed
Downloaded and installed MySQL database from https://dev.mysql.com/downloads/windows/installer/5.7.html.

 Documentation
MySQL is a popular open-source relational database management system (RDBMS) widely used in web applications, data analysis, and various other domains. To install MySQL on your machine, follow these steps:

1. Visit the official MySQL website (https://dev.mysql.com/downloads/) and download the appropriate installer for your operating system.
2. Run the installer and follow the on-screen instructions. During the installation process, you'll be prompted to set a root password for the MySQL server.
3. After the installation is complete, open a terminal or command prompt and run the following command to verify the installation:
   
   mysql --version
   
   This should display the installed version of MySQL.



 6. Set Up Development Environments and Virtualization (Optional)

 Action Performed
No action was performed for this step.

 Documentation
Setting up development environments and virtualization tools can be beneficial for isolating project dependencies, ensuring consistent environments across different machines, and simplifying deployment processes.

Docker is a popular open-source platform for building, deploying, and running applications in containers. Containers provide a lightweight and portable way to package an application along with its dependencies and runtime environment, ensuring consistent behavior across different systems.

Virtual machines (VMs) are another approach to creating isolated development environments. VMs emulate a complete operating system and hardware environment, allowing you to run multiple operating systems and configurations on a single physical machine.

 Challenges:
- Learning the concepts and tools for containerization (Docker) or virtualization


 7. Explore Extensions and Plugins

 Action Performed
No action was performed for this step.

 Documentation
Most text editors and IDEs offer a wide range of extensions and plugins that can enhance your development experience by adding new features, improving productivity, and integrating with various tools and services.

For Visual Studio Code, you can explore and install extensions by following these steps:

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the square icon in the left sidebar or by pressing Ctrl+Shift+X.
3. In the Extensions view, you can browse and search for available extensions.
4. Install the desired extensions by clicking the "Install" button.

Some popular and useful extensions for Visual Studio Code include:

- Python (for Python development)
- Git Lens (for Git integration and visualization)
- Prettier (for code formatting)
- Live Server (for live reloading of web applications)
- Docker (for Docker integration)

Challenges:
-  some extensions added to the cpu power consumption there by making vs-code slower
