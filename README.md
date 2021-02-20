# ABAP BDC_BP_CREATE
ABAP BDC Program to create Business Partners for Sales Order creation

Go to SE38 & create the attached program :
 
Execute the program.
 
In parameter P_File, provide the excel sheet with details of partners in the below format:
Column 1: First name of the Partner
Column 2: Street
Column 3 : House Nr
Column 4 : Post Code
Column 5: City
Sample data sheet:
 
In parameter E_FILE; give any text file path. In P_MODE; write N to execute in background.
It takes approx. 1 min to create each BP. The program executes in background.

# ABAP PARTNER_PROFILE_COPY

A sample partner profile say 9980005150 will be used as an example to create Partner Profiles for other partners. Go to transaction SE38 & upload the program:
 
Execute this program. In the parameter P_FILE, give the path of excel with the BPs which exist in the system. A sample excel with columns MANDT, Partner Number & Partner Type is attached below.

 
In the parameter PARTN_S give the number of the Sample partner profile i.e the partner whose partner profile is to be copied.
