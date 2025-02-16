# Tic-Tac-Toe_React
Learning react fundamentals with tic-tac-toe

This project follows along with a tutorial found here: 
https://react.dev/learn/tutorial-tic-tac-toe

I am working in the Pop!OS linux distro with VSCode.
I followed the instructions on the page to work with this code locally.

    1. Install Node.js 
        -I used these commands found in this Odin Project Module:
         https://www.theodinproject.com/lessons/foundations-installing-node-js

            -sudo apt install curl

            -sudo apt update && sudo apt upgrade

            -curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash

            -export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
            [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

            -command -v nvm #verify the install

            -nvm install --lts

            -nvm use --lts

    2. In the CodeSandbox tab you opened earlier, press the top-left corner button to open the menu, and then choose Download Sandbox in that menu to download an archive of the files locally. 
        -I downloaded the zip file to desktop and moved it into the directory for this repo and unzipped it there.

    3. Unzip the archive, then open a terminal and cd to the directory you unzipped

    4. Install the dependencies with *npm install*
        -I ran into problems here, I was getting error messages referring to dependency issues upstream with React. I queried solutions to the error by running a prompt with the error message through Gemini and reading the suggested trouble shooting steps and following a few that I felt were worth a try. At this point I am a little beyond my level of expertise. Here are the commands I ran:

            -npm install -g npm@11.1.0

            -npm install react-scripts@latest

            -npm fund

            -npm uninstall react

            -npm install react@18

            -npm cache clean --force

            -npm install react@18.3.1

            -npm install --force

        -I ran these commands based on the trouble shooting suggestions in Gemini, the output I was receiving from each command and what I felt I did understand based on my current skill level. After this I moved onto the next step and to my surprise I found that a new tab opened in my browser, running the code locally as desired!


    5. Run *npm start* to start a local server and follow the prompts to view the code running in a browser

I don't understand all of what came in the zip folder from the project creators or what I was able to accomplish to make the code run locally. I did attempt to get it running locally so that I could provide documentation of my project as I follow along and learn the fundamentals of React. In this repo I included the files that I felt would show my interaction with this tutorial project and my ability to edit the code in a clear and well documented way. These documents are:
    -index.html
    -App.js
    -index.js
    -styles.css
The directories public/ and src/ are left exactly as they were in the tutorials zip folder. I added this document to the public/ directory. 