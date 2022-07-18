# Preparation for Class
If you run into any issues, you can try googling the error message, or you can email us. If you aren't able to figure it out on your own, please email jasmine.stone@columbia.edu. We will help you troubleshoot before class starts so that everyone can start on the same page.

## Video Introductions to Command Line and Git
1. [Introduction to the Command Line (5m 40s)](https://www.youtube.com/watch?v=cgVbqxtx3hU)
2. [Introduction to Git (Watch the first 6m 32s)](https://www.youtube.com/embed/uR6G2v_WsRA?end=392). The remainder of the video is good to watch for an introduction to how we will be using git in class, but is not necessary if you are short on time.
3. [Introduction to Git Remotes / Github (Watch from 1:30-4:48 )](https://www.youtube.com/embed/Gg4bLk8cGNo?start=90&end=288)
4. [Introduction to Conda / Package Managers (Watch the first 6m 56s)](https://www.youtube.com/embed/23aQdrS58e0?end=416). The remainder of the video is good to watch and provides a good introduction to how we will be using conda in class, but is not necessary if you are short on time.

## Set up Conda
### Check if Conda is already installed
- Open terminal using the following instructions for your operating system. (Instructions taken from [this source](https://docs.microsoft.com/en-us/learn/modules/python-install-vscode/)).
    - Mac:
        1. Open the Terminal app by pressing Command + Spacebar key combination to search by using Spotlight.
        2. In the search box, enter Terminal. In the results set select Terminal app, and then press Return to start the app.
    - Windows:
        1. Install Windows Terminal using [these instructions](https://docs.microsoft.com/en-us/windows/terminal/install). Use Powershell.
        2. Open Windows Terminal. Whenever instructions say to use terminal, this is the terminal you will use.
    - Linux: 
        1. Open a Linux terminal session. The instructions for opening this session depend on your distribution and version of Linux. Check the online documentation for your Linux distribution for instructions on how to open a terminal session.
- Check if conda is already installed by typing `conda --version` in terminal and pressing enter.
- If the output says conda and a version number, e.g. `conda 4.12.0`, skip to installing VSCode.
- If you get an error message, install miniconda as follows.

#### Installing Miniconda
- Download the version of miniconda for your machine [listed here](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links)
    - [Windows instructions for figuring out your system architecture](https://pcguide101.com/cpu/what-is-my-processor-architecture/)
    - Mac instructions for figuring out your system architecture:
        1. click on Apple icon in top left corner > About This Mac
        2. Look at the Chip in the Overview.
        3. Select the appropriate miniconda download link ending in `.pkg`
    - Linux: The first option under linux should be appropriate for your computers.
- Install the downloaded miniconda
- Check that the install worked by closing terminal if it is open, reopening it, and typing `conda --version`. The output should say conda and a version number, e.g. `conda 4.12.0`


## Install VSCode
- Follow the instructions for your operating system (Linux, Windows, or Mac) here: https://docs.microsoft.com/en-us/learn/modules/python-install-vscode/
- Troubleshooting:
    - If `code .` doesn't work for you, try using the Uninstall 'code' command in the PATH command before the "Install 'code' command in PATH" command following the instructions [here](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line) ([source](https://stackoverflow.com/questions/29955500/code-is-not-working-in-on-the-command-line-for-visual-studio-code-on-os-x-ma)).
    - For Linux, you can download either a .deb or a .rpm file. Which one you should use depends on your distribution, more specifically whether it is Debian- or Redhat-based. (Ubuntu, for example, is Debian-based and would need a .deb file.)


## Make a Github Account
- Go [here](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) to make a github account. I would recommend using an academic email because students get github pro for free, but you can always add other email addresses to your profile later. 


# Resources
- [Git Cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)
- [Command Line Cheatsheet](https://www.educative.io/blog/bash-shell-command-cheat-sheet)
- [Conda Cheatsheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
