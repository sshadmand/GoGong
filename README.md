# Welcome to GoGong
An open source screenshot capture and server link creator. 

Learn more at https://sshadmand.github.io/GoGong/

GoGong has two components:

 1. A native OSX application

 2. A DJANGO server that accepts posts made from the app and return a sharable URL


### Native OSX Application
 
The native OSX application is written in swift and is available as source code or as an app you can install on your OSX machine. The app upload the latest screen capture taken and pastes the returned sharable URL into you machine's clipboard for easy pasting.
 
### Server

A DJANGO server that accepts posts made from the app and return a sharable URL.

## Reason for Being
I needed a capture & share solution that could run entirely on an Intranet (or heavily firewalled) environemt. Of course, there are many awesome capture & share tools out there, but they all have some component based on top a public cloud; and that just wouldn't do. Since there may be others with the same need, I decided to build a solution and open-source it.
