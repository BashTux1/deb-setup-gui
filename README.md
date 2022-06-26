# deb-setup-gui
Written for Debain  
Which includes "whiptail" by default to display dialog boxes from shell scripts  

This is a GUI script for setting up system basics, such as networking and timezone.  
It can easily be adapted to any other Distro. 

Please check the code to ensure you know what it is going to be doing.  
Use at your own risk.

This is meant as inspiration or as a general guide on how to achieve a working GUI
with the ability to do some error checking before applying the configuration.

![](gui.gif)  

I recently found the need to create a similar GUI for a Linux Appliance system/server for my work,  
which provides an easy way for customers without Linux knowledge to set a static IP as well as  
set the system timezone and NTP etc...  
I was not able to find a full working example of this need, and so thought I would share my work  
which took a fair bit of time to get the validation parts workings (which seem easy now in hindsight)  

Hopefully this is helpful to someone else out there ;) 
