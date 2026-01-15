## Calls-Metrics

This repository holds the Jupyter notebook and csv files to process raw data from the dialer software (Xencall/Readymode)
and convert it into the format needed for the input into the company´s reports for visibility and follow up purposes. 

It takes as input the information placed into the CSV file dowloaded from Readymode report called "Project Metric", 
which has the following format: "1 hour, 3 min., 21 s." for every time value.
The transformation script returns a file with the converted format which is the standard HH:MM:SS that the organizational report "Metrics" needs, 
saving it into "Formatted Metrics - YYYY-MM-DD" which is completely ready to upload to the mentioned report.
