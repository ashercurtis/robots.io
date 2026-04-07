## Loop through google drive spreadsheet

This bot does: A connector to google drive and loop through the rows of a targetted spreadsheet. Write to the console log the item ID, the name of the item and the quantity remaining. 

Requires saving an example csv to google sheets called fruit_db.csv:
Item,Name,Quantity
f_01,Apple,7
f_02,Orange,12
f_03,Grape,60

Bot will also perform an if statement to identify Apples versus not Apples by iterating for each row of the spreadsheet. 


#Set up
1. Save the csv as a google sheet on your google drive in a easy to remember location. 
2. Connect to google drive using your credentials (Google Sheets) and then navigate to the spreadhseet location on google drive (Spreadsheet).   
