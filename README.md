# GITPull-Server

I created this program for my team to pull the git on the server without accessing the ssh or remote desktop.

Due to manual git pull on the server and the hassle of logging in on SSH or Remote Desktop.

And, if you don't allow your dev team to log in on your server via SSH/RDP to make a git pull. Use this.

So, by using this app, you give your dev team a way to make a git pull on its way without bothering you to do it or without giving them access to your server via SSH or RDP.

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

Then, you access it on your browser. `http://localhost:21885/pull` or `http://localhost:21885/pull?branch=main`

Or, watch my video sample on youtube. - [Youtube/Git Pull over the Browser](https://youtu.be/J4BEja5SI-E)

## Notes

Be sure you allow the ./gitserver to your privacy policy if you are a mac m1 user (Full Disk Access)

And, be sure that you can git pull on your project via terminal before using this app.
