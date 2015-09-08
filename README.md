While planning my conference sessions for .conf2015 I decided it would be fun and easier to do this in Splunk.  
The app allows you to view,filter and plan your sessions a Gantt chart.  

I got the dataset using a combination of https://conf.splunk.com/speakers.html and the Agenda planner.  The raw data was then passed into splunk and correlated to build the csv file found in the lookups directory.

###screenshots
![Screenshot 1](https://raw.githubusercontent.com/stash1001/dotconf2015/master/appserver/static/Screenshot1.png "Screenshot 1")
![Screenshot 2](https://raw.githubusercontent.com/stash1001/dotconf2015/master/appserver/static/screenshot2.png "Screenshot 2")

Credits go to Alex Iribarren for creating the Ganntt Chart which can be found here https://splunkbase.splunk.com/app/1741/ 
