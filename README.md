# with-basics

## Mac Setup
- download and install [iterm](https://iterm2.com/downloads.html)
- download and install [node](https://nodejs.org/en/download/)
  - be careful to install the correct version(64 vs arm64)

- open iterm and verify node is installed
  - `node -v`  should display the version of node that is installed

- create a folder to keep projects/repositories in
  - create a folder named `dev`
    - in iterm navigate to `/Users/<computer name>`
    - in iterm `mkdir dev`
    - should create `/Users/<computer name>/dev`

## Download Repo
- navigate to `dev` folder
- clone repo
   - `git clone https://github.com/peteplays/with-basics.git`


## Running App
- navigate into created folder
  - `cd with-basics`
- install dependencies
  - `npm install`
- start app
  - `npm start`
  - should open a browser window displaying `index.html`
  - this is using a server with live reloads, so as changes are made they will automatically be displayed
