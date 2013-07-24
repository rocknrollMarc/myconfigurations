#Hough Workstation Configurations: OSX
---
This setup will backup your existing configuration files and hook up various text editor configurations,
application mappings, sets of my favorite functions and utilities, and a few other goodies.  Use this setup 
at your own risk, and if you find bugs please let me know in git or ping me on twitter @chrishough. 

[Grok - Trunk - Live](http://www.youtube.com/watch?v=Qi_AAqi0RZM&feature=share)

Let's start by getting the manual steps out of the way first:

1. open terminal
2. cd $home
3. mkdir .myconfigurations
4. cd .myconfigurations
5. git clone git@github.com:chrishough/myconfigurations.git .
6. sh buildsystem.sh

When you kick off the build system script it will process the following:

1. cd $home
2. mkdir .myconfigurations-backups

