# Preparation for Class
Please try to follow the instructions to [Set Up Conda](https://github.com/Columbia-Neuropythonistas/IntroPythonForNeuroscientists2022/blob/main/Week01_SetUpEnvAndHelloWorld/README.md#set-up-conda) and [Install VSCode](https://github.com/Columbia-Neuropythonistas/IntroPythonForNeuroscientists2022/blob/main/Week01_SetUpEnvAndHelloWorld/README.md#install-vscode) by Sep 6 so that we have time to troubleshoot and everyone can start on the same page. Once you've set everything up, take a screenshot of the printed hello world, a screenshot of the conda version, and submit both to Courseworks. Please also fill out the pre-class survey form by then. If you run into any issues, you can try googling the error message, or you can email us. If you aren't able to figure it out on your own, please email jasmine.stone@columbia.edu.

Please do the rest of the preparation before the first class.

## Fill Out Pre-Class Survey [Form](https://forms.gle/b4uv61rAjPQ8bMRy7)
Now that you've decided to take the class, we would like to get a sense of people's previous experience and what they want to get out of the class in case this is different than in the interest form we sent out last year. Form [here](https://forms.gle/b4uv61rAjPQ8bMRy7).

## Video Introductions to Command Line and Git
1. [Introduction to the Command Line (5m 40s)](https://www.youtube.com/watch?v=cgVbqxtx3hU)
2. [Introduction to Git (Watch the first 6m 32s)](https://www.youtube.com/embed/uR6G2v_WsRA?end=392). The remainder of the video is good to watch for an introduction to how we will be using git in class, but is not necessary if you are short on time.
3. [Introduction to Git Remotes / Github (Watch from 1:30-4:48 )](https://www.youtube.com/embed/Gg4bLk8cGNo?start=90&end=288)
4. [Introduction to Conda / Package Managers (Watch the first 6m 56s](https://www.youtube.com/embed/23aQdrS58e0?end=416) and also [the end of the video from 15:50 on)](https://www.youtube.com/embed/23aQdrS58e0?start=950) The remainder of the video is good to watch and provides a good introduction to how we will be using conda in class, but is not necessary if you are short on time.

## Set up Conda
### Check if Conda is already installed
- Open terminal using the following instructions for your operating system. (Instructions taken from [this source](https://docs.microsoft.com/en-us/learn/modules/python-install-vscode/)).
    - Mac:
        1. Open the Terminal app by pressing Command + Spacebar key combination to search by using Spotlight.
        2. In the search box, enter Terminal. In the results set select Terminal app, and then press Return to start the app.
    - Windows:
        1. Check if you have anaconda prompt installed. If not, it is unlikely that you have conda installed. Go directly to 'Installing Miniconda'.
    - Linux: 
        1. Open a Linux terminal session. The instructions for opening this session depend on your distribution and version of Linux. Check the online documentation for your Linux distribution for instructions on how to open a terminal session.
- Check if conda is already installed by typing `conda --version` in terminal and pressing enter.
- If the output says conda and a version number, e.g. `conda 4.12.0`, submit a screenshot of this to the courseworks assignment and skip to installing VSCode.
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
- Windows users: you will now use 'Anaconda Prompt (Miniconda3)' as your terminal from here on out. Check that it installed properly by searching for it in your start menu and opening it.
- Check that the install worked by closing terminal if it is open, reopening it, and typing `conda --version`. The output should say conda and a version number, e.g. `conda 4.12.0`. Submit a screenshot of this to the courseworks assignment.


## Install VSCode
- Follow the instructions for your operating system (Linux, Windows, or Mac) here: https://docs.microsoft.com/en-us/learn/modules/python-install-vscode/
- As a reminder, once you've gone through the instructions above, please take a screenshot of your printed hello world, and submit it on the courseworks.
- Troubleshooting:
    - If `code .` doesn't work for you, try using the Uninstall 'code' command in the PATH command before the "Install 'code' command in PATH" command following the instructions [here](https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line) ([source](https://stackoverflow.com/questions/29955500/code-is-not-working-in-on-the-command-line-for-visual-studio-code-on-os-x-ma)).
    - For Linux, you can download either a .deb or a .rpm file. Which one you should use depends on your distribution, more specifically whether it is Debian- or Redhat-based. (Ubuntu, for example, is Debian-based and would need a .deb file.)


## Make a Github Account
- If you don't have a github account already, go [here](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) to make one. I would recommend using an academic email because students get github pro for free, but you can always add other email addresses to your profile later. 
- Submit your github username to this [google form](https://forms.gle/idAGheSfm6VCspwq9).


# Resources
- [Setting up Git SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## Cheatsheets
- [Git Cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet.pdf)
- [Command Line Cheatsheet](https://upload.wikimedia.org/wikipedia/commons/7/79/Unix_command_cheatsheet.pdf)
- [Conda Cheatsheet](https://docs.conda.io/projects/conda/en/latest/_downloads/cb0ffc4c7b1e6c0e716c066d2b077faf/conda-4.12.pdf)
