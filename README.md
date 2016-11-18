# wgitwatch

A simple version of gitwatch for Windows Users.
This batch file will automatically stage, commit and push your repository

Dump this somewhere (usually C:\) and create Task in Task Scheduler to run every x minutes (depending on how paranoid you want to be).

On the task main window you need to check the "Hidden" box. 
Despite the “Hidden” box being checked in the Scheduled Task properties, a batch script can still appear as a window on your desktop. 

The key to making this window not appear is to configure the task to “Run whether user is logged on or not” in the task’s properties.

After switching to this option, you will have to enter the appropriate credentials since the task will now run unattended, and that's it.