Brief:

Exercise #1 Join to Range:
A company in Australia has source data which is made up of a series of postal codes (eg. 2000, 2001, 2002 etc.) amongst some other data fields. They have a separate reference table which contains postcode ranges (eg. 2000 to 2002) which they would like to use to match/filter their main data.
Each Customer Record needs to be joined to the Lookup table based on a Postal Area Ranged region. Then finally summarize the customer data by Region, Sales Rep, and Responder, then a count of customers.
Check and see what the result should look like by looking at the data labeled 'Output'.  Your mission is to take the input files and blend them so your result matches the output shown.

Link: https://community.alteryx.com/t5/Weekly-Challenges/Challenge-1-Join-to-Range/td-p/36621


Solution 1: Workflow 1
- Utilized the Formula tool to define the min and max values to generate sequential numbers.
![Ex1_S1](https://github.com/ShamleeBhoi/Alteryx/assets/162983736/d85892aa-0081-44c3-a8c8-f85f4d363da5)


Solution 2: Workflow 2
- Utilized the Text-to-Coloumn tool to split the series postal codes.

Solution 3: 
- Utilzed pandas code in jupyter using the python tool to generate the postal code coloumn and then use the Alteryx summarize to generate the output.

Solution 4:
- Carry the entire soluter using pandas and python functions. 
