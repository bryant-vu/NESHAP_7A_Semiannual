# NESHAP_7A_Semiannual
Automate minute temp data rollup to 3HR avgs

NESHAP_7A.exe is intended for LTR’s semiannual NESHAP 7A report.


The following provides background information:

•	40CFR63 Subpart AAAAAAA requires semiannual reports submitted to EPA indicating facility compliance.
•	A deviation is defined as a 3 hour average I-301 temperature of less than 1400F. 
•	The program will output an Excel file titled “YYYY_MM_DDD to YYYY_MM_DD NESHAP 7A” at location of ‘T.csv’ file.   (For example, if the ‘T.csv’ file is located in a folder titled “Data”; the program will create “YYYY_MM_DDD to YYYY_MM_DD NESHAP 7A” in the “Data” folder).
•	The program requires the input file to be the ‘T.csv’ file from the DCS monthly reports.  
