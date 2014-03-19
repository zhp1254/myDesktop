myDesktop
=========

python remote desktop programe (like vnc)

Introduction
============
This program implemented the server and the client, the client can control and view the server's desktop, just like using a local computer these operations, the client can use the keyboard and mouse to control the server

Main of Libraries and APIs
==================
* The network communication used twisted and socket to achieve
* The GUI used PyQt4
* qt4reactor


##### The Keybaord and Mouse control:
* Linux    --> X11 library 
* Mac OS X --> AppKit, Quartz import
* Windows  --> win32api, ctypes


Platform
========
* Linux
* Mac OS X
* Windows

Screenshots
===========
##### myDesktop Server
<img  src="https://raw.github.com/jacklam718/myDesktop/master/screenshots/myDesktopServer.png" alt="myDesktop Server"  width="450px" height="250px" />

##### the myDesktop client remote to server
<img src="https://raw.github.com/jacklam718/myDesktop/master/screenshots/myDesktopViewer.png" alt="myDesktop Client"
width="450px" height="250px"/>

##### the myDesktop client remote to server to watch YouTube
<img src="https://raw.github.com/jacklam718/myDesktop/master/screenshots/myDesktopViewer2.png" alt="myDesktop Client"
width="450px" height="250px"/>
