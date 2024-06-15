[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280484&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   Prequisites- Windows 11 OS, User permissions
   Steps:
   Step 1: Download Visual Studio Code
a. Open a Web Browser: Open your preferred web browser e.g Chrome.
b. Visit the Visual Studio Code Website: Go to the official Visual Studio Code website.
c. Download the Installer:
On the homepage, you will see a "Download" button. Click on it.
The website should automatically detect your operating system and provide the appropriate installer for Windows (User Installer).

Step 2: Install Visual Studio Code
a. Run the Installer:Once the download is complete, open the installer file (VSCodeSetup-x64-<version>.exe).
b. Accept the License Agreement:When the installer starts, read the license agreement.
c. Check the box to accept the agreement and click Next. Select Installation Location:
d. Choose the destination folder where you want to install VS Code. The default location is usually fine.
e. Click Next. Select Additional Tasks: You will be prompted to select additional tasks. Here are some recommended options:
Create a desktop icon: Check this box if you want a shortcut on your desktop.
e. Add to PATH: This is important for using VS Code from the command line. Ensure this box is checked.
f. Register Code as an editor for supported file types: This is optional but useful.
g. Click Next. Install: Click the Install button to start the installation process.
h. Launch Visual Studio Code: Once the installation is complete, you can choose to launch Visual Studio Code immediately by checking the Launch Visual Studio Code box.
h. Click Finish.

Step 3: Initial Setup and Configuration
a. Open Visual Studio Code:If you didn’t choose to launch it during the installation, open VS Code by double-clicking the desktop icon or finding it in the Start menu.
b. Install Recommended Extensions (Optional): You might be prompted to install recommended extensions depending on your previous setups or installations.
You can choose to install extensions for languages like Python, JavaScript, etc., by clicking on the Extensions icon in the sidebar or pressing Ctrl+Shift+X.
c. Configure Settings (Optional):
d. Customize your VS Code settings by clicking on the gear icon in the lower left corner and selecting Settings.

Verification
a. To verify that Visual Studio Code is installed correctly: Open VS Code:
Ensure that the application opens without errors.
b. Check Command Line Access: Open Command Prompt or PowerShell and type code to ensure that VS Code opens from the command line, indicating that the PATH was set correctly.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
 a. Theme and icons
 b. font settings
 c. Word wrap
 d. Indentation settings

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
  1. Activity Bar
a. Purpose: The Activity Bar is located on the far left side of the VS Code window. It provides quick access to different views and functionalities.
b. Components:
-Explorer: Icon resembling a file folder. It allows you to navigate and manage your project files and folders.
-Search: Magnifying glass icon. Provides search functionality across files.
-Source Control: Git icon (branch symbol). Integrates with version control systems like Git, allowing you to manage source code changes.
-Run and Debug: Bug icon. Provides options for running and debugging your code.
-Extensions: Puzzle piece icon. Allows you to browse, install, and manage extensions that extend the functionality of VS Code.
2. Side Bar
a. Purpose: The Side Bar is located next to the Activity Bar on the left side of the VS Code window. It contains views and panels that provide additional functionalities related to your project and workspace.
b. Components:
-Explorer: This shows the file and folder structure of your project. You can navigate, create, delete, and manage files and folders here.
-Search: Provides search functionality across files in your project.
-Source Control: Shows changes in your Git repository and allows you to commit, pull, push, and manage branches.
-Extensions: Lists installed extensions and allows you to browse the VS Code Marketplace for more extensions.
3. Editor Group
a. Purpose: The Editor Group is the main area where you edit and view your code and files. VS Code supports multiple editor groups, allowing you to work on multiple files simultaneously.
b. Components:
- Tabs: Each open file or editor is represented by a tab at the top of the Editor Group. You can switch between files by clicking on their respective tabs.
-Split View: You can split the Editor Group vertically or horizontally to view and edit multiple files side by side.
4. Status Bar
a. Purpose: The Status Bar is located at the bottom of the VS Code window. It provides information about the current state of your project and the actions you can perform.
b. Components:
- Language Mode: Displays the programming language of the current file.
- Line and Column Numbers: This shows your current cursor position in the file (line number and column number).
- Encoding: Displays the file encoding format (e.g., UTF-8).
- Line Endings: Indicates the line ending format used in the file (e.g., LF or CRLF).
- Git Branch: If your project is under version control with Git, it shows the current branch name.
- Notifications and Extensions: Displays notifications about tasks, errors, and warnings. Extensions can also add information and actions to the Status Bar


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   -A command palette is a powerful tool that allows you to access various commands, settings and features through a searchable interface. It provides a quick way to execute commands without needing to remember specific keyboard shortcuts or navigate through menus.
   -To open the Command Palette in VS Code: Windows: Press Ctrl+Shift+P.
   -Common tasks- Navigating between files, command execution, searching for files, extension management, debugging, settings

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   -The extensions in VS code allow the coder to extend functionality beyond the features of the code editor.
   -Users can sezrch for and install extensions from the command palette- extensions. Extensions can be uninstalled, disabled or updated.
   Examples of essential extensions include- live server, debugger, path intellisense and git lens

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   -Integrated terminal is opened from the View > Terminal in the top menu, or use the Command Palette (Ctrl+Shift+P) and search for View: Toggle Integrated Terminal.
   -The Integrated terminal is used for: debugging, running commands, interacting with Git
   -Advantages of using the integrated terminal include: seamless integration, allows customization and promotes efficiency, allows extension integration.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   -To create a new file, click on the explorer icon, then right click on the parent directory where you want to create a file, select new file, enter a name for the filenad plress enter to create the file
   -To open a new folder, right click on the parent directory in the explore view, slect new folder and provide a name for the folder. Press enter to create the folder.
   -Managing files and folders includes steps like- renaming, deleting, moving and copying
   - To navigate between files and folders, several options could be used: Using the explore view, using short cuts. 


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
-Users can customize settings on VS Code from the settings view 
- To change the theme, font size and keybindings- open settings, seach for 'colour themes', 'font sizes' and key bindings. Make changes according to your preferences and save changes.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   To debug, open your project, configure the settings, set break points then start debugging.
   Some key debugging features on VS include: Variable Inspection, Watch Expressions, Call Stack, Conditional, Breakpoints, Exception Handling, Console 

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    - To integrate Git with VS code, ensure that Git and VS code are both installed
    -process:
    1.initialize Git repository
    2.Stage files for commit
    3.Commit changes
    4.Link your repository to git hub
    5.Add remote repository
    6.push changes
    

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

