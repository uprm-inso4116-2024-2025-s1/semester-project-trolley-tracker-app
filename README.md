# Semester-project-trolley-tracker-app

## 🎉 ¡Join Our Groups! 🚀 
[![Join Discord](https://img.shields.io/badge/Join_Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/u3KT8zJm)
[![Join WhatsApp](https://img.shields.io/badge/Join_WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/KcCF9TWb9BM1R5ifLV03D5)


## IMPORTANT: This is NOT the repo which in which we're currently working on for our Software Design Class

- Go to the "uprm-inso4116-2024-2025-s1" organization and select the "RUMBus-Dashboard" repository. That's where we're implementing our tasks


----------------------------------------------------------------
----------------------------------------------------------------


## Instructions on how to run the RUMBus-Dashboard Project:

### I. Windows:

1.  If you do not have it yet, install the latest Node.js version from:
    https://nodejs.org/en/download/prebuilt-installer

2.  Install Yarn using Command Prompt or Powershell.
    Run the following command: npm install --global yarn
    For further information, revise the documentation in:
    https://classic.yarnpkg.com/en/docs/install#windows-stable

3.  Run Powershell as Administrator or Command Prompt and
    go to C:\Windows\system32\ (be careful please). Run the command:
    Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted
    Then, type Y for yes.

4.  Go to the project and run the following command on the terminal:
    yarn install

        IMPORTANT: If you get the error "The engine "node" is incompatible with this module",
        is because you will require Node.js to be version 22.0.0 or above to be able to use the
        module @angular/animations@18.2.3. To solve this:

        a. Install Node Version Manager from https://github.com/coreybutler/nvm-windows/releases.
        Go to Assets, install nvm-setup.exe and execute the installer.

        b. On Command Prompt or Powershell, run the command nvm install 22. Then run the command
        nvm use 22.

5. Go to the project terminal and type the following command:
    yarn start

6.  Lastly, open your browser of choice with: http://localhost:4200/

7.  DONE

### II. MacOS:

1. Clone the RUMBus-Dashboard repo into your IDE of choice (i.e VS Code)

2. Install Homebrew by running the following instruction on Terminal:
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

3. If you do not have it yet, install the latest Node.js version in your Terminal. 
   You may find the commands to install it from: https://nodejs.org/en/download/package-manager

4. Install Yarn by running: brew install yarn

5. Go to where the project is located on your device and install NPM
   by running: yarn install

6. Once installed, start Yarn by running: yarn start

7. Finally, open your browser of choice with: http://localhost:4200/

8. DONE

----------------------------------------------------------------
----------------------------------------------------------------

## IMPORTANT: Whenever the codebase is updated, remember to:

   a. Git pull
   
   b. Run "yarn install", then "yarn start" on your terminal
   
   c. Go to http://localhost:4200/

### Docker Commands:

docker-compose -f docker-compose.prod.yml up --build
shows in http://localhost

docker-compose -f docker-compose.dev.yml up --build
shows no connection or "Connection has reset"

How to run the Local Backend (Currently empty):

