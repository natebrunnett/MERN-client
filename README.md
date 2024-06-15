# Introduction
Hi, if you already have NPM installed, you can simply clone this repo and install the node_modules with:

    cd into a mud folder
    $ git clone <link>
    $ cd MERN-client && npm i
    $ npm start

If the npm start command works you can get started with web development. However, to modify and make greater changes, it's best to learn VSCode, Gitbash and Node Packet Manager.  Which are all ultimately easy to use, in fact you may not even need VSCode at all, if you know how to use Nano.

# MERN-client

This tutorial is intended for a Window's User to install all necessary software
to get started with a MERN developer's work flow from the client side.

# Prerequisites
    1) Visual Studio Code installed
      1.1) download => https://www.code.visualstudio.com
        1.01) This installation is easy, you download the .exe and keep clicking next
    2) Node Packet Manager installed
      1.1) download => https://nodejs.org/en/
      1.2) Choose the LTS version (Long Term Support)
      1.3) Download and run the .msi
        1.01) Click next and install
        1.02) Note - Chocolatey can also be installed via the .msi (optional)
            1.001) Chocolatey is an installer for windows that is useful for other programming languages
      1.4) Restart your apps
    3) Gitbash installed
      1.1) download => https://www.git-scm.com/downloads 
        1.01) Most OS are 64 bit, so download this unless otherwise
        1.02) Launch the .exe
        1.03) Keep clicking next, some of the check prompts are useful though
        1.04) Successful Installation
        1.05) Relaunch VSCode to make sure it is embedded in the editor
    4) Knowledge of Gitbash commands

# Tutorial : Generating the client
    1) VSCode => Open Folder
      1.1) cd into a mud folder (I like to have a mud folder)
      1.2) Make a new folder, Let's call it `React_Project_1`

    2) Cmd + J to open a terminal
      1.1) Open a Git Bash term by clicking the down arrow located next to the plus
       1.01) `$ cd React_Project_1`
       2.01) `$ npx create-react-app client`
       3.01) `$ cd client && npm start`
         1.001) http://localhost:3000 in the browser should navigate to your running client
    
    3) That is all for now. To set up the server proceed to the MERN--server-from-Scratch repo.  
