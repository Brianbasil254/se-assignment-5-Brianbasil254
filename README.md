[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281791&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
         - Download:
            - Go to the Visual Studio Code download page.
            - Select the installer for Windows (User Installer or System Installer).
         - Run Installer:
            - Open the downloaded .exe file.
            - Accept the license agreement.
            - Choose the installation location or keep the default.
            - Select additional tasks (optional), such as adding to PATH and creating a desktop icon.
         - Install:
            - Click "Install" and wait for the process to complete.
            - Click "Finish" to launch Visual Studio Code.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
        Theme:
        - Go to File > Preferences > Color Theme.
        - Choose a theme that suits your preference (e.g., Dark+, Light+, etc.).

        Font Size and Family:
        - Navigate to File > Preferences > Settings.
        - Search for "Font Size" and adjust it as needed.
        - Search for "Font Family" to change the font.

        Extensions:
        - Open the Extensions view by clicking the Extensions icon on the Activity Bar or pressing Ctrl+Shift+X.
        - Install essential extensions, such as:
               - Prettier: Code formatter.
               - ESLint: Linting JavaScript.
               - Python: Support for Python development.
               - Live Server: Launch a local development server with live reload.
  
        Auto Save:
        - Enable auto-save by going to File > Preferences > Settings and searching for "Auto Save".
        - Set to "afterDelay" or another preferred option.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
       Activity Bar:
       - Located on the far left.
       - Provides access to different views, such as Explorer, Search, Source Control, Run and Debug, and Extensions.
  
       Side Bar:
       - Displays the contents of the selected view from the Activity Bar.
       - For example, the Explorer view shows your project files and folders.

       Editor Group:
       - The central area where you edit files.
       - You can split the editor into multiple groups by right-clicking on a tab and selecting "Split".

       Status Bar:
       - Located at the bottom.
       - Shows information about the current file and project, such as line number, column number, language mode, and any active extensions or tasks.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
       - The Command Palette is a powerful tool in Visual Studio Code (VS Code) that provides quick access to various commands and functionalities without needing to navigate through menus. It allows you to execute tasks, switch settings, and run scripts by typing the command name, making it a highly efficient way to work.
       - Accessing:
         - Press Ctrl+Shift+P or F1 to open the Command Palette.
       - Common Tasks:
         - Open Settings: Type "Open Settings".
         - Install Extensions: Type "Extensions: Install Extensions".
         - Change Theme: Type "Preferences: Color Theme".
         - Run Code: Type "Run Code" (requires Code Runner extension).

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   - Extensions enhance the functionality of VS Code, allowing for language support, themes, debugging tools, and more.
  Finding Extensions:
   - Open the Extensions view with Ctrl+Shift+X.
   - Use the search bar to find specific extensions.
  Installing Extensions:
   - Click on the desired extension and click "Install".
  Managing Extensions:
   - Use the Extensions view to disable or uninstall extensions.
  Essential Extensions for Web Development:
     - Prettier: Code formatter.
     - ESLint: JavaScript linter.
     - Pylace
     - Python
     - intellisence
     - JavaScript.
     - css.  

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
       - Opening Terminal:
            - Press Ctrl+`` (backtick) or go to View > Terminal`.
    Advantages:
       - Seamless integration with the editor.
       - Supports multiple terminals in one window.
       - Allows running and debugging scripts within the same environment.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
       Creating:
         - Right-click in the Explorer view and select "New File" or "New Folder".
       Opening:
          - Double-click on files in the Explorer view to open them in the editor.
       Navigating:
         - Use Ctrl+P to quickly open files by name.
         - Use Ctrl+Tab to switch between open files.
         - Use breadcrumbs (at the top of the editor) for navigating directories.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
      Accessing Settings:
        - Go to File > Preferences > Settings or press Ctrl+,.
      Changing Theme:
         - Search for "Color Theme" and choose your preferred theme.
      Adjusting Font Size:
         - Search for "Font Size" and set your desired size.
      Changing Keybindings:
        - Go to File > Preferences > Keyboard Shortcuts or press Ctrl+K Ctrl+S.
        - Modify keybindings by clicking the pencil icon next to the command.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
         Open Debug View:
           - Click the Run and Debug icon in the Activity Bar or press Ctrl+Shift+D.

         Configure Debugger:
           - Click on "create a launch.json file" to configure your debug settings.
         Set Breakpoints:
           - Click in the gutter next to the line numbers in your code to set breakpoints.
         Start Debugging:
           - Click the green play button or press F5.
         Key Debugging Features:
           - Breakpoints: Pause execution at specific lines.
           - Watch: Monitor variables and expressions.
           - Call Stack: View the call stack and navigate the code.
           - Variables: Inspect and modify variable values.
10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
         Initialize a Repository:
           - Open the Source Control view by clicking the Source Control icon in the Activity Bar.
           - Click "Initialize Repository".
         Making Commits:
           - Stage changes by clicking the + icon next to the files.
           - Write a commit message in the input box and click the checkmark icon to commit.
         Pushing Changes to GitHub:
           - Write the command 'git push'
         Connecting to GitHub:
           - Use the built-in GitHub authentication in VS Code.
           - Click the "Clone Repository" button in the Source Control view and provide the repository URL.
           - Follow the prompts to authenticate with GitHub and clone the repository

 Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July
