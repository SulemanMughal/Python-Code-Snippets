#   Check Website Connectivity


This script includes a basic utility for checking website connections.


Website URLs should be listed one per line in the input file websites.txt.


A two-column report with the URL of each tested site and its state is included in the output file website **status.csv**.


The script just checks for a **200** status code from the webserver.


Each time you run the utility, the result file will be overwritten.


#### Libraries Required

-   csv
-   requests