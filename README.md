# AZMET Web Scrapper
This pogram uses Microsoft Excel VBA to pull raw data from the AZMET weather station for certain locations. It is pulling data for precipitation, reference et value, and reference et "Penman Monteith".  I have created a Sub procedure for data type being pulled from the AZMET website. For each Sub procedure there are two different sub functions being called to pull or write data on the spreadsheets. The spreadsheet will require input from the user for start date and end date.  This will be located at "B1" (Start Year) and "B2" (End Year). While inputing the year use only the last two digits for the years you will be pulling from. This is needed for the program to be read in the correct year for the format of the webpage it will be pulling from. So for example you would have to put "17" instead of "2017", not doing this will result in an error after you try to run the program. After reading in the year the program will look for the station number located on row "6" starting on column "B". The station number is used for the URL to pick a certain weather station.  In this section you will be able to add more stations by just inputing the station number at the next empty column. If the Station number is starting with a "0" be sure to turn the cell you are working into a Text cell. Now all you have to do is press button to start the web data pull and it will display the progress on the bottom left status bar.  
