##copy files bot (google docs)
This bot provides a loop that searchs a google drive folder for files that will be copied/backedup into a new folder on google documents. 

The backedup/copied file has a sufix of "_bk" and the date in yyyMMdd format to distinguish between backup dates. Files backedup/copied multiple times in a day are replaced. Console logs each iteration in the loop. 

Desktop and web studio compatible.

#Set-up:
1. Connect to google drive using your comnnection
2. set the input location folder in the "For each file or folder In location" activity.
3. Set the output location folder in the "Copy File File to copy" activity.