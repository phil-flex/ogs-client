# ogs-client
OGS Online-go.com Desktop Client

This OGS client actually the electron browser visit the https://online-go.com site. It can remember the login status and create tray icons in the Desktop. Logically this electron project also works for MacOS, but I don't have it.

#Setup

Node.js required

1. npm install
2. npm pack:electron

Setup in electron_app/dist/

#Know issues

1. Login page may redirect to new Windows and it is required to refresh the page by using dev tool. (Ctrl-Shift-i) then (Ctrl-R) to refresh page. Once login, it will no need to login again.
2. It does not support the message notification.