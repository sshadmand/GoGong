# Welcome to GoGong
An open source screenshot capture and server link creator. 

## Reason for Being
With all of the new (and quite awesome) capture & share tools out there, I found none offered a completely cloudless solution. One that can be run entirely on an intranet or heavily firewalled environemt where no information or traffic should be let out. So I built my own and offered it up to anyone who wants it.

Forbidden City


Learn more at https://sshadmand.github.io/GoGong/

GoGong has two components:

 1. A native OSX application

 2. A DJANGO server that accepts posts made from the app and return a sharable URL


### Native OSX Application
 
The native OSX application is written in swift and is available as source code or as an app you can install on your OSX machine. The app upload the latest screen capture taken and pastes the returned sharable URL into you machine's clipboard for easy pasting.
 
### Server

A DJANGO server that accepts posts made from the app and return a sharable URL.
