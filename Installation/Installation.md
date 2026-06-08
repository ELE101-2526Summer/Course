# ELE101

ELE101 Course Installation Repo

## Installation
**Download** as zip file or **clone** this repo into your system. After that extract it if necessary, then change into the folder.  

We will be using **conda** to install tools necessary for the rest of the course. I prefer installing **miniconda** which is faster and it includes less packages. If you have conda (miniconda or anaconda) already installed you may skip conda installation section, jump into create an environment. 

Installation depends on the operating system you use. So, follow one of the following sections depending on your system. Installation steps for Linux and Mac users are nearly the same. 

### Windows
Install miniforge for Windows from this [address](https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-Windows-x86_64.exe). This will install base environment with Python 3.9. For Windows, double click on the downloaded installer executable and follow the prompts. By default, this will install miniforge to your user directory at C:\Users\USERNAME\miniforge3 (if you choose install only for me, **preferred**) or C:\ProgramData\miniforge3 (in case you choose install for all users) and add a "Miniforge Prompt" entry to your start menu. Running the "Miniforge Prompt" should bring up a console window where your base conda environment is activated and you can use the conda command. 

So, first start a **miniforge prompt**, this will bring up a console with (base) at the beginning. Create an environment using command below. This will install lots of packets in verbose mode. So you will see lots of messages in your terminal. It will take a few minutes to finish, depending on your speed and your PC configuration (3-4 minutes in my case). 

    conda config --append channels conda-forge
    conda create --name ELE101 --file requirements.txt

### Linux and MacOS
Run `./install.sh`. This will download and install miniforge, create an environment, then install all necessary packages for you. Mac users should install **Homebrew** to use wget. wget can be installed with `homebrew install wget`. 

# Good Luck!
Need help, feel free to reach me at ytregitim@gmail.com. 

Wish you good luck in installation!
