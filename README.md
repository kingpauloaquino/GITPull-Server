# GITPull-Server

Due to always manual git pull on the server and the hassle of logging in on SSH or Remote Desktop.

I created a program to be able for my team and me to pull the git on the server without access to ssh or remote desktop

## Usage

Use config.json to change the IP Address and Port number. Recommended not to change the IP Address. Only the port number

Prerequisites, you should download and install the [git windows](https://git-scm.com/download/win) or
[git macos](https://git-scm.com/download/mac) or [git linux](https://git-scm.com/download/linux) and set up your account.

Download and pick the app based on your machine (If you are using MAC-M1, use the specific app for that machine), Config.json, and Git-Server. Then, please copy and paste it inside your project directory.

I.e.:

YourWebProject

- Index.php
- .....
- config.json
- gitserver

If all set, run the gitserver for Linux/Mac `./gitserver`

Then, you can access it on your browser. `http://localhost:21885/pull` or `http://localhost:21885/pull?branch=main`

## Notes

Be sure you allow the ./gitserver to your privacy policy if you are a mac m1 user (Full Disk Access)

And, be sure that you can git pull on your project via terminal before you use this app
