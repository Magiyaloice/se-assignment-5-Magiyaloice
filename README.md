[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15271954&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   To download the VS Code visit https://code.visualstudio.com/download. On the platform specific guide select "download for windows". This will download the installer file.
   ![alt text](<vs code.PNG>)
   Once the download is complete, locate the downloaded installer file.Double click on it to run it. The VS Code setup wizard will open.Click 'next'to continue.Select 'add PATH'environment variable.
   Optional(select 'create a desktop icon')
   Click on the install button and the setup will begin. Click on the finish button, once the installation is complete.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   
   After installing VSCode, the following initial configurations and settings might be adjusted;
      Extensions: explore and install extensions that will enhance your workflow.
      Examples of extensions : python, git lens, CODE Runner etc. 
      Open the settings by clicking on the gear icon in the bottom left corner, and customise settings like theme, font size and the editor workspace.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   
   Activity bar:
         Usually on the left side of the window,the activity bar contains icons for different views and panels in VS Code.
   Side bar:
         Positioned on the left side of the window,the side bar contains several views (explorer,search,source control,run and debug,extensions), that help with navigation and managing projects.
   Editor group:
          This is the part of the window where files are opened for editing.Each file is opened in a tab within an editor group.
   Status Bar:
         Located at the bottom of the window, the status bar provides information about the current file and editor status. 
          

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   It is a feature that allows users to execute commands quickly without navigating through menus.
   To access it, click on the View in the menu bar then select command pallette, or you can use a shortcut by pressing ctrl+shift+p.
   The command pallette can be used to execute commands, access settings and prefences, install extensions,navigate between views and run tasks.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   The role of extensions is to enhance the functionality and customization capabilities of VS Code.
   To access extensions press ctrl+shift+X.
   Examples of essential extensions for web development include: HTML CSS Support, GitLens- Git supercharged,Path intellisense, Prettier - Code formatter 

   [alt text](<vs code 1.PNG>)

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   To open go to View then select Terminal or use the command pallette (ctrl + shift + p). 
   The advantages of using intergrated terminal is:
      - you can manage version control systems, run scripts without leaving the code editor in VS Code.
      -you can customise the terminal settings.
    
7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   To create a file - click on the File button in the menu bar and select 'New file'
          or use the shortcut (ctrl +alt + windows+ N).
          Select file type and also name your file.
   Managing your file- right click on the file and select whether you want to rename delete or move       
          To rename, enter the new name and press Enter to confirm.
          To cdelete, confirm the deletion when prompted.
          To move, navigate to the destination folder and right-click in the explorer panel.select paste to move or copy the file

 

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   Click on the gear icon located in the bottom left corner of the activity bar. 
   View and modify settings to match your workflow and preferences.

   To change themes select themes in the settings bar then select 'color theme', File icon theme' or 'Product icon theme'.
   To change font size, select settings in the settings menu then workspace.Select text editor to change font size.
   To customize keybindings, go to settings then keyboard shortcuts.Search for specific actions and assign custom keybindings 

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   1. install the neccessary debugger extensions for your programming language, if not already installed.
   2. create a Launch configuration
   3. Select the appropriate configuration from the list that matches your environment
   4.  configure launch settings
 


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

   -Integrating Git with Visual Studio Code for version control allows the user to manage your codebase   efficiently
   - In the Git terminal, navigate to your project directory.
   - Initialize a new git repository with the command 'git init'. A new Git repository will be created in your directory.
   - Open your project in VS Code and make changes. 
   - In the terminal stage changes to files for inclusion in the next commit
   - Once you've staged changes, enter'git commit' to commit your changes. 
   - Push your changes to Github using the command 'git push'.



 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

