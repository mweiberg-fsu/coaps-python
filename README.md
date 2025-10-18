# COAPS Python Toolbelt & Tutorial
The COAPS Python Toolbelt & Tutorial is designed to get users up and running with a Python environment. Below is a list of software/IDEs that are considered industry standard. 

## Software Utilized

### Managing Environments
We need some software that can manage environments and store our Python libraries. Anaconda is a powerful software bundle that allows us to create as many environments as we want and provides an additional launchpad for installing other tools! This is important when we are working on multiple projects with different libraries or wanting to share projects with other users.
- **Anaconda** - Python distribution for data science with built-in package management.

### Integrated Development Environment (IDE)
We need to install an IDE to allow us to build out our scripts, projects, and eventually plots! Below are three industry standard tools that can allow us to do this. I would recommend just choosing one for now based on your comfort level. Additional details are provided below with images to help you decide!
- **Visual Studio Code** - Versatile IDE with debugging and extension support.
- **Pycharm** - Advanced IDE with code completion, debugging, testing, and project management features.
- **Jupyter Notebook** - Interactive IDE for writing and running code with visuals and notes.

### Additional Tools
While it is important to understand the fundamentals of Python and the syntax it utilizes, we don't need to fly in the dark! GitHub Copilot can be natively installed via extensions in Visual Studio Code or PyCharm. This is essentially an AI coding assistant that can help the onboarding process for those just being introduced to Python. We'll also install Git Bash, which is a terminal line command tool that lets us keep our files, plots, and scripts externally for access from other users or other devices!

- **GitHub Copilot** - AI assistant that suggests and completes comments/code in real time.
- **Git Bash** - A terminal utility command-line tool that lets us keep our files externally on GitHub.

### Additional Files
Some sample data files in .csv are available as well as a guide to download weather data for specific weather stations in Florida. In addition, there is a Notebook file that can be launched in an IDE or a weather_data.py file to showcase some of the amazing features that Python has to offer for categorizing and displaying data!


## Table of Contents
- [Anaconda](#anaconda)
- [Visual Studio Code](#visual-studio-code)
- [Jupyter Notebook](#jupyter-notebook)
- [PyCharm](#pycharm)
- [Python Libraries](#python-libraries)
- [Getting Sample Data](#getting-sample-data)
- [Start Coding](#start-coding)
- [GitHub Integration](#github-integration)

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
> It can take 20-30 seconds to load in, but should have something like this below

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

2. Let’s get our terminal up and running! From the menu bar, go to view -> Terminal, or use the shortcut **CTRL + `**

> [!NOTE]
> In Windows, this can be done by going to **Terminal -> New Terminal**

![VS Code Terminal Launch](https://i.imgur.com/P6kS0pv.png)

3. After our terminal has launched at the bottom of our IDE, we can activate our python environment that we created in Conda! This can be done by typing in `conda activate [ENVIRONMENT NAME]`.

![VS Code Terminal](https://i.imgur.com/JDN2NVu.png)

### Part 3: Activating GitHub Copilot
As students (or anyone with a .edu email), we can get GitHub Copilot for free! This utilizes ChatGPT to provide AI assistance while coding. This is particularly useful for providing comments (or vice versa, writing a comment and having Copilot simulate the code). This can significantly reduce time required for coding or providing comments.

1. Go to the Extensions view by clicking the Extensions icon in the Activity Bar (square icon on the left) or using Cmd + Shift + X.

![VS Code Extensions](https://i.imgur.com/UeSUxRs.png)

2. Search for "GitHub Copilot" and install the official extension from GitHub.

![VS Code Copilot](https://i.imgur.com/2JfzTcB.png)

3. Sign in with your [GitHub Account](https://GitHub.com/). You'll be redirected to a browser to authorize VS Code.

> [!TIP]
> You can find the GitHub Copilot widget at the bottom right of VS Code, near the terminal.

![GitHub Login](https://i.imgur.com/nNQt31K.png)

4. Once signed in, Copilot is activated! 
    - To test: Open a .py file, type a comment or function signature, and Copilot will suggest code—press Tab to accept.

## PyCharm
PyCharm provides an excellent IDE for managing large projects, as well as integrating Notebooks and scripts.

### Part 1: Installing PyCharm
1. PyCharm's download location can be launched from Anaconda

![PyCharm Anaconda Install](https://i.imgur.com/9QCBFwH.png)

> [!NOTE]
> Direct download link can be found here: https://www.jetbrains.com/pycharm/data-science/?var=anaconda

2. Click the **Download** link after the web page launches

![Install PyCharm](https://i.imgur.com/sDm6Jdj.png)

> [!IMPORTANT]
> At COAPS, make sure to select **.dmg (Intel)**

3. Once the .dmg file has been downloaded, launch it and drag **PyCharm** to the **Applications folder**

![PyCharm to App Folder](https://i.imgur.com/lFKSA7F.png)

4. PyCharm is now installed and ready to go! You can start a Notebook file (see Jupyter below), scripts, or entire projects with PyCharm.

![Pycharm Installed](https://i.imgur.com/S2xFt5m.png)

### Part 2: Installing Copilot for PyCharm
1. GitHub Copilot can be installed via **Plugins** 

![Copilot for Pycharm](https://i.imgur.com/wFbkwwM.png)

2. After installing the plugin and restarting PyCharm, the Copilot plugin can be found on the bottom right after opening a script. Login with your GitHub account!

![Copilot login for Pycharm](https://i.imgur.com/e8JPQ7S.png)

> [!NOTE]
After GitHub Copilot is activated, suggestions will now appear in your script! Hitting **Tab** will accept suggestions.

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
Now that we have our Python environment and IDE set up, we need to get some Python libraries/modules. Essentially these are plugins for Python that allows us to perform various tasks without needing to code the functions/utilities ourselves!

### Method 1: Installing Python Libraries on Mac
1. Open a Terminal window in Mac from the App folder

![Terminal](https://i.imgur.com/DKBNNLg.png)

> [!TIP]
> If it’s already running, you can create a new tab at the top via ‘Shell’ -> ‘New Tab’ -> ‘New Tab with…’

![Terminal Tab](https://i.imgur.com/O5l93f5.png)

2. In the new Terminal window, type in `conda activate coaps` (or whatever you called your environment earlier), see previous step in VS Code!

3. After our environment is active, type in `pip install pandas`. It’ll run a bunch of commands like below. 

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

### Method 3: Installing Python Libraries in PyCharm
1. Much like VS Code, PyCharm also allows us to launch a terminal and install modules. 

![PyCharm PIP](https://i.imgur.com/X2Fz10O.png)

> [!IMPORTANT]
> Make sure we activate our Anaconda environment first with `conda activate [ENVIRONMENT NAME]` and then do `pip install [PYTHON MODUEL]`

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
> After running `weather_data.py` in VS Code, we should get output in the terminal from our prints.

![Example Output](https://i.imgur.com/Cqwo24B.png)

## GitHub Integration
Since we already created an account on GitHub for Copilot, we might as well utilize it! GitHub allows us to **create repositories**, **upload** (called **push** in GitHub) our files/plots, and **download** (called **pull** in GitHub). This way, we can share files among multiple devices, keep version history, and even share our GitHub repos with other people!

### Step 1: Git Bash
We don't want to manually upload files, so let's get some additional software that lets us do this from a terminal! 

1. Navigate to https://git-scm.com/downloads and click MacOS at COAPS

![Git Download](https://i.imgur.com/6HYb3AS.png)

2. There are a few ways we can install Git, the easiest is to try this command in a terminal after activating our environment `brew install git`

> [!TIP]
> Some Macs may prompt you to download git after doing `git --version` in a terminal if it's not installed.

> [!IMPORTANT]
> If **Homebrew** is not installed, run this command in the terminal `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

### Step 2: Create Credentials on GitHub
We need to do some set up for our new GitHub account so we can properly have credentials! 

1. After logging into GitHub, **navigate to the top right image** (your profile image) and go to **Settings**

![GitHub Profile Settings](https://i.imgur.com/Ev5SgP4.png)

2. On the **left sidebar of options**, scroll all the way to the bottom and **select the last option, Developer settings**

![GitHub Developer Settings](https://i.imgur.com/0nddn5E.png)

3. Open **Personal Access Tokens** and select **Tokens (classic)**

![GitHub Token Access](https://i.imgur.com/gDj40rS.png)

4. Select **Generate new token** from the dropdown box in the middle

![GitHub Token Selection](https://i.imgur.com/7KExjrN.png)

> [!IMPORTANT]
> Make sure to **select Generate new token (classic)** when creating our new token.

5. On the next screen, give our credentials any note

!**Note** you want and set the Expiration to **No expiration**

![GitHub Token Creation](https://i.imgur.com/8eruYU9.png)

> [!IMPORTANT]
> For scopes here, make sure to at least select **repo**. You can **select all of them** if you prefer!

6. One last step here. On the next page, we will get a **Token hash** that typically starts with **ghp_...**. Make sure to **save this entire line in a file/notepad** somewhere!

![GitHub Token Hash](https://i.imgur.com/NmdUmo2.png)

### Step 3: Create a New GitHub Repo

After logging into GitHub, we can access our Dashboard on the left! 

1. Where it says **Top repositories** click on the green **New** button.

![GitHub Repo](https://i.imgur.com/VuoKEX5.png)

2. On the next screen, **give our repo a name** and **create it**!

![alt text](https://i.imgur.com/KjYfNCU.png)

> [!TIP]
> If you don't want your repo **to be public** to everyone, you can **set Visibility** from **Public** -> **Private**. You can still invite **Collaborators** at a later date!

3. We want to run these two lines in a Mac terminal (or in your IDE terminal):
    - ``git config --global user.name "Your Name"``
    - ``git config --global user.email "your@email.com"``

> [!IMPORTANT]
> The **Git username and email** should match what you made for your GitHub account earlier.

4. Navigate to an empty directory on your computer (or make a new folder). Let's create our first GitHub repo locally! Run these commands in a terminal after navigating to this folder
    - `echo "# coaps-test" >> README.md`
    - `git init`
    - `git add README.md`
    - `git commit -m "first commit"`
    - `git branch -M main`

> [!NOTE]
> This will (1) **create an empty README.md file** we can add comments to, (2) **initialize our local repo**, (3) **add our new file** locally, (4) **create a commit** with a comment, and (5) **create a branch**

> [!TIP]
> We can **make a directory** right from the terminal by using the command `mkdir [FOLDER_NAME]`

5. On the main GitHub repo page we just created, **you will have a unique url** (in addition to the commands we just ran above). **Copy that line** with the url:
    - `git remote add origin https://github.com/mweiberg-fsu/change-this-to-your-repo.git`
    - `git push -u origin main`

![GitHub Repo](https://i.imgur.com/pSzWk1M.png)

> [!IMPORTANT]
> The first time you send a **push** command, it will prompt you for a password. **Use that hash code** we saved earlier when we created a personal token!

![Terminal Commands](https://i.imgur.com/kDQaA23.png)

6. That's it, we're all set! **Navigate back to our GitHub repo** in a browser window, and you should see your files!

![alt text](https://i.imgur.com/R8U0GXC.png)

### Step 4: Quick GitHub Commands to Remember
Here are some quick Git commands to use when **pushing and pulling** files from different devices.

1. Let's say we want to download our files on a laptop. If we **navigate back to our GitHub page**, we can select the **green <> Code button**, this will give us a URL to copy so we can clone our repo!

![GitHub Clone](https://i.imgur.com/Hx92dps.png)

2. After **navigating to a directory** you want to save your repo at (see steps above), **run this command in a terminal**
    - `git clone https://github.com/mweiberg-fsu/change-this-to-your-repo.git`

> [!TIP]
> Make sure to change the url above to your unique url.

3. This should **download all the files** and **create a local GitHub repo** on your laptop now!

4. If you ever want to update your files and **push** them to your external GitHub repo, **run these commands** in succession
    - `git add .`
    - `git commit -m "add some comments on what you changed"`
    - `git push`

That's it! You now can **keep your external and local GitHub repos up-to-date and share** them with other people. This is great for putting projects on your resume at a later date as well!