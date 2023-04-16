In the default discovery, the Freelancer Public Gamelist Server is disabled, meaning that we can't see the server yet. Why did they do that? Don't ask me...
1. Browse to your Discovery Freelancer install (where you were in step 2.3)
2. Go into the EXE directory
3. Edit Freelancer.ini with Notepad. *Troubleshooting step:* If it is read only, you will have to unset it, right click the file > properties > uncheck Read-only > OK
4. Scroll down or otherwise find the section that begins with [ListServer]
5. Remove the ; from the line with hostname, it should look like *hostname = http://gun.fllistserver.com/*
6. Save the file
 
![Editing the Freelancer.ini file](./assets/images/UnCommentOut.PNG)