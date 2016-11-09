# MirrorOS
MirrorOS is a new platform for smart mirrors that focuses mainly in interactivity featuring voice commands and a smarthpone remote app. It runs web apps which are easy to build and has a set of APIs that developers can use to easily integrate voice commands and smartphone remote control.

**NOTE**: This project is in a very early phase. You can expect bugs and crashes. It has only beeen tested on a Raspberry Pi 3.
##Installation
Download and run 
```npm install```
and then
```npm start```
##Configuration
Most apps will need access to API keys from different services to fully work. Edit the config.js file and add your own API keys.
In this file you can also set the default home app and the default assistant app as well as enabling gesture support but this requires you to have the appropiate sensors to work.
##Hardware requirements
- Raspberry Pi 2 or 3
- USB microphone

##Apps
####Home app
Shows weather and date information. Can set reminders.
#####Super app (Assistant)
This is a Sri-like app. You can ask it anything.
#####YouTube app
Watch YouTube videos.
#####News apps
Shows news from differnet sources. Not customizable yet.
##Remote control app
You can control MirrorOS from any device that has a browser by going to the IP address that's shown on the top left of the screen. It's specially useful with a smartphone.
From the remote control app you can install other apps, launch apps and use your smartphone's microphone to send commands to the mirror.
##Building apps for MirrorOS
Coming soon... In the meantime check the source of the included apps. They are all in the "apps" folder.