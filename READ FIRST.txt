ImageComparison
===============

A combination of software to monitor webpages as you change them
By: Bridger Hahn

===============

Unzip this to C:\

C:\WebImages will be created automatically

===============

!!  An installation of Webshot is necessary. It can be downloaded at http://www.websitescreenshots.com/

  Modify the webshotcmd-it shortcut contained in this project to point to your webshotcmd. DON'T REMOVE THE /in!!!
	
!!  An installation of CutyCapt is also necessary. It can be downloaded at http://cutycapt.sourceforge.net/

  In bin\bat\variableSet, change the cuty variable to point to your installation of CutyCapt.
	
!!  Add any URLs that you wish to have recorded to the URLs.txt file, one line each.

!!  populateVerified will populate the Verified folder with images of the current state of the websites, as viewed from IE.

!!  startupBatch will run the program. It may take a long time, depending on the number and size of webpages being monitored.

  You must either manually put verified images of the websites in the Verified folder or run populateVerified before running startupBatch.	

!!  If you wish for the program to run automatically at scheduled times, use Windows Scheduler.