# with-basics

## Mac Setup

- download and install [vsCode](https://code.visualstudio.com/download)
- install prettier for vsCode [Prettier Formatter for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - this will format code on save
- download and install [iterm](https://iterm2.com/downloads.html)
- download and install [node](https://nodejs.org/en/download/)

  - be careful to install the correct version
    - 64 intel macs
    - arm64 are M1 macs

- open iterm and verify node is installed

  - `node -v` should display the version of node that is installed

- create a folder to keep projects/repositories in
  - create a folder named `dev`
    - in iterm navigate to `/Users/<computer name>`
    - in iterm `mkdir dev`
    - should create a folder named `dev`
      - `/Users/<computer name>/dev`

## Download Repo

- navigate to `dev` folder
- clone repo
  - `git clone https://github.com/peteplays/with-basics.git`

## Running App

- navigate to repo folder
  - `cd with-basics`
- install dependencies
  - `npm install`
- start app
  - `npm start`
  - should open a browser window displaying `index.html` served at `http://localhost:5555/`
  - this is using a server with live reloads, so as changes are made they will automatically be displayed
