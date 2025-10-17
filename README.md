# COAPS Python Toolbelt & Tutorial
The COAPS Python Toolbelt & Tutorial is designed to get users up and running with a Python environment. Below is a list of software/IDEs that are considered industry standard. 

## Software Utilized
- **Anaconda** - Python distribution for data science with built-in package management.
- **Visual Studio Code** - Versatile code editor with debugging and extension support.
- **Jupyter Notebook** - Interactive tool for writing and running code with visuals and notes.
- **GitHub Copilot** - AI assistant that suggests and completes comments/code in real time.

## Anaconda
1. The first thing we need to do is download and install Anaconda. This will get all the tools we need for Python and let us set up environments
    - Download link: https://www.anaconda.com/download/success

> [!IMPORTANT]
> Make sure to switch the **‘Download for Mac’ to Intel** with the dropdown arrow when at COAPS.

![Anaconda Installer](https://i.imgur.com/H3VHcce.png)

2. Once we get that installed, we should have a screen that looks like this

![Anaconda Installed](https://i.imgur.com/aBA8xxs.png)

3. If you **click on ‘Environments’** on the left, and then **‘Create’ on the bottom left**, you can set up a new environment (name it whatever you want).

> [!TIP]
> It can take 20-30 second to load in, but should have something like this below

![Anaconda Env](https://i.imgur.com/9XQxNV5.png)

## Visual Studio Code
Now that we have Anaconda installed and our Python environment running, let's go get an IDE!

### Part 1: Installing Visual Studio Code
1. Go to the VS Code download page: https://code.visualstudio.com/download
2. Under the macOS section, look for the x64 (Intel) options

> [!NOTE]
> You can choose the .zip file for a simple installation (recommended for most users) or the User/System Installer if you prefer a guided setup.

> [!IMPORTANT]
> Download the x64 version to ensure compatibility with your Intel Mac.

![VS Install](https://i.imgur.com/uvwTXou.png)

3. Once downloaded, open your Downloads folder in Finder.
    - If you downloaded the .zip file, double-click it to extract the contents: this will give you the Visual Studio Code.app file
    - Drag the Visual Studio Code.app file to your Applications folder. You’re good to go!

### Part 2: Setting Up a Workspace and Terminal In VS Code
After launching visual studio code, there are a few things we need to do.

1. Let’s setup a workspace! This is essentially adding a directory for where our files will be located. This can be done via **File -> Add Folder to Workspace**

![VS Code Workspace](https://i.imgur.com/N8fWrsp.png)

2. Let’s get our terminal up and running! From the menu bar, got to view -> Terminal, or use the shortcut **CTRL + `**

> [!NOTE]
> In Windows, this can be done by going to **Terminal -> New Terminal**

![VS Code Terminal Launch](https://i.imgur.com/P6kS0pv.png)

3. After our terminal has launched at the bottom of our IDE, we can activate our python environment that we created in Conda! This can be done by typing in `conda activate [ENVIRONMENT NAME]`.

![VS Code Terminal](https://i.imgur.com/JDN2NVu.png)

### Part 3: Activating GitHub Copilot
As students (or anyone with a .edu email), we can get Github Copilot for free! This utilizes ChatGPT to provide AI assistance while coding. This is particularly useful for providing comments (or vice versa, writing a comment and having Copilot simulate the code). This can significantly reduce time required for coding or providing comments.

1. Go to the Extensions view by clicking the Extensions icon in the Activity Bar (square icon on the left) or using Cmd + Shift + X.

![VS Code Extensions](https://i.imgur.com/UeSUxRs.png)

2. Search for "GitHub Copilot" and install the official extension from GitHub.

![VS Code Copilot](https://i.imgur.com/2JfzTcB.png)

3. Sign in with your [GitHub Account](https://github.com/). You'll be redirected to a browser to authorize VS Code.

> [!NOTE]
> You can find the GitHub Copilot widget in the bottom right of VS Code, near the terminal.

![Github Login](https://i.imgur.com/nNQt31K.png)

4. Once signed in, Copilot is activated! 
    - To test: Open a .py file, type a comment or function signature, and Copilot will suggest code—press Tab to accept.