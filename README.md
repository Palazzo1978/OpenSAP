OpenSAP
This is a Python software that tries to read and work data from a SAP SQL Database extraction
The software works using Python Pandas libriaries

The software mainly it will be structured into four parts :
* Read table from SAP SQL Database extraction
** Join SAP table and create Pandas Dataframe
*** Create useful reports
**** Distribute these reports to the SAP users

# Read Tables

##How to test
Every file end with a ("row numbers" rows affected)
You must be sure that the file cancel just this row and the total number of rows taken by python is correct.

## Mara -
for the table structure see :
http://www.se80.co.uk/saptables/m/mara/mara.htm

KeyField are MANDT and MATNR
Datatype
