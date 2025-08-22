## Calls-Metrics

This repository holds the Jupyter notebook and csv files to process raw data from the dialer software (Xencall/Readymode)
and convert it into the format needed for the input into the company´s reports for visibility and follow up purposes. 

It takes as input the information placed into the CSV file "Daily_raw" with format example "1 hour, 3 min., 21 s." 
and returns a file with the converted format which is the standard HH:MM:SS that reports require, saving it into
"Daily_fixed" when running the notebook named "Daily_report.ipynb".
