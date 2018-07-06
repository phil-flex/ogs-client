# ogs-client
## OGS Online-go.com Desktop Client

This OGS client actually the electron browser visiting the https://online-go.com site. It can remember the login status and create tray icon in the Desktop. 

Logically this electron project should also support for MacOS, but I don't have it, so haven't tried that.

# Setup

git is required to download this source code or you can download and extract from zip file provided by github.

1. git clone https://github.com/phil-flex/ogs-client.git

Node.js required, download from https://nodejs.org/en/download/ and install the stable edition.

Then open "Command Prompt", type "cmd" in Start menu and run the following command.

1. npm install
2. npm run pack:electron

Setup files in electron_app/dist/, find the OS platform corresponding setup file, `OGS Client Setup 0.0.2.exe`.

# Preview
https://ibb.co/jCdX2J

# Usage

Run `OGS Client` from start menu
Stop it via right click tray icon, select "Exit".
