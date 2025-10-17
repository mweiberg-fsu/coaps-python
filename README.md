# COAPS Python Toolbelt & Tutorial
The COAPS Python Toolbelt & Tutorial is designed to get users up and running with a Python environment. Below is a list of software/IDEs that are considered industry standard. 

## Software Utilized

### Managing Environments
We need some software that can manage environments and store our Python libraries. Anaconda is a powerful software bundle that allows us to create as many environments as we want and provides an additional launchpad for installing other tools! This is important when we are working on multiple projects with different libraries or wanting to share projects with other users.
- **Anaconda** - Python distribution for data science with built-in package management.

### Integrated Development Environment (IDE)
We need to install an IDE to allow us to build out our scripts, projects, and eventually plots! Below are three industry standard tools that can allow us to do this.
- **Visual Studio Code** - Versatile Integrated Development Environment (IDE) with debugging and extension support.
- **Jupyter Notebook** - Interactive IDE for writing and running code with visuals and notes.
- **Pycharm** - Advanced IDE with code completion, debugging, testing, and project management features.

### Additional Tools
While it is important to understand the fundamentals of Python and the syntax it utilizes, we don't need to fly in the dark! Github Copilot can be natively installed via extensions in Visual Studio Code or PyCharm. This is essentially an AI coding assistant that can help the onboarding process for those just being introduced to Python.

- **GitHub Copilot** - AI assistant that suggests and completes comments/code in real time.

## Table of Contents
- [Anaconda](#anaconda)
- [Visual Studio Code](#visual-studio-code)
- [Jupyter Notebook](#jupyter-notebook)
- [PyCharm](#pycharm)
- [Python Libraries](#python-libraries)
- [Getting Sample Data](#getting-sample-data)
- [Start Coding](#start-coding)

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
> Download the x64 version to ensure compatibility with your Intel Mac at COAPS.

![VS Install](https://i.imgur.com/uvwTXou.png)

3. Once downloaded, open your Downloads folder in Finder.
    - If you downloaded the .zip file, double-click it to extract the contents: this will give you the Visual Studio Code.app file

> [!TIP]
> Drag the Visual Studio Code.app file to your Applications folder. You’re good to go!

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

## PyCharm
1. PyCharm download location can be launched from Anaconda

[PyCharm Anaconda Install](https://i.imgur.com/9QCBFwH.png)

> [!NOTE]
> Direct download link can be found here: https://www.jetbrains.com/pycharm/data-science/?var=anaconda

2. Click the **Download** link after the web page launches

[Install PyCharm](https://i.imgur.com/sDm6Jdj.png)

> [!IMPORTANT]
> At COAPS, make sure to select **.dmg (Intel)**

3. Once the .dmg file has been downloaded, launch it and drag **PyCharm** to the **Applications folder**

[PyCharm to App Folder](https://i.imgur.com/lFKSA7F.png)

4. PyCharm is now installed and ready to go! You can start a Notebook file (see Jupyter below), scripts, or entire projects with PyCharm.

[Pycharm Installed](https://i.imgur.com/S2xFt5m.png)

## Jupyter Notebook
I strongly recommend using Visual Studio Code or PyCharm, it is the industry standard IDEs for computer science and programming! Nevertheless, Jupyter Notebook provides a modular coding environment, and will be used by various professors. It has its advantages for being user friendly and to quickly test coding segments.

1. In Anaconda, going back to ‘Home’, click ‘install’ for Jupyter Notebook.

![Jupyter Install](https://i.imgur.com/zHPmWPV.png)

2. Launch it after install, and it should load something like this in your web browser

![Jupyter Launch](https://i.imgur.com/Rum60en.png)

3. Create a folder anywhere you want, and inside that folder hit **‘New’ and then ‘Python 3 (ipykernel)’**

> [!NOTE]
> This will create a new **.ipynb file** (name it whatever you want)

![Jupyter File](https://i.imgur.com/8PVnXR8.png)

4. After that, you’re ready to go! You can add additional cells to run different code at different times.

![Jupyter Launch](https://i.imgur.com/EvbwM4k.png)

## Python Libraries
Now that we have Python environment and IDE set up, we need to get some Python libraries/modules. Essentially these are plugins for Python that allows us to perform various tasks without needing to code the functions/utilities ourselves!

### Method 1: Installing Python Libraries on Mac
1. Open a Terminal window in Mac from the App folder

![Terminal](https://i.imgur.com/DKBNNLg.png)

> [!NOTE]
> If it’s already running, you can create a new tab at the top via ‘Shell’ -> ‘New Tab’ -> ‘New Tab with…’

![Terminal Tab](https://i.imgur.com/O5l93f5.png)

2. In the new Terminal window, type in `conda activate coaps` (or whatever you called your environment earlier), see previous step in VS Code!

3. After our envrionment is active, type in `pip install pandas`. It’ll run a bunch of commands like below. 

![Python Module](https://i.imgur.com/sjFJUTy.png)

> [!TIP]
> While we're at it, let's install additional Python libraries we will need later.

- `pip install matplotlib`
- `pip install plotly`
- `pip install numpy`

### Method 2: Installing Python Libraries in VS Code
1. This can also be done in Visual Studio Code!

2. Once your conda environment has been activated, you can type in `pip install [PYTHON MODULE]`

![VS Code PIP](https://i.imgur.com/P2jNmVD.png)

## Getting Sample Data
1. We can get some csv data from here for a bunch of different weather stations in Florida - https://climatecenter.fsu.edu/climate-data-access-tools/downloadable-data

![Data URL](https://i.imgur.com/FsLkbiU.png)

> [!TIP]
> After navigating to the link above, make sure to select ‘All’ for variable and a year range for the station you select

2. This will download a .csv file, which has a unique name (you can change this name to whatever convention you want!)

> [!IMPORTANT]
> Move this data file to your main directory (where your python file or .ipynb exists) to access it

## Start Coding
We're all set up and can now start coding and plotting data!

1. Attached in this GitHub Repo are some sample files and data to start with.
    - `data.csv` is the data file we downloaded earlier.
    - `weather_data.py` is a sample Python file with comments that will create plots.
    - `weather_data.ipynb` is a sample Jupyter file with comments that will create plots.

![Files](https://i.imgur.com/xKp3in3.png)

> [!TIP]
> After running `weather_data.py` in VS Code, we should get output in the terminal our prints.

![Example Output](https://i.imgur.com/Cqwo24B.png)

