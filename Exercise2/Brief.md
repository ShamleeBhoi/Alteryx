Exercise 2: 

Many products will export textual data with delimiters such as quotes.  This is done so that strings can contain delimiters or control characters within them.   Having more than one type of delimiter can be hard for ETL programs to interpret.  In the input text file, there are two different delimiters (double quotes, single quotes) and they surround different data types.
Use Alteryx to strip out the delimiters as superfluous and format the data as represented in the output

Solution 1:


![image](https://github.com/ShamleeBhoi/Alteryx/assets/162983736/e5b12c85-2c85-44f5-bb65-51283b572257)

Used the text-to-coloumn tool separate data from single field to delimiter based coloumn, then trim the " and ' quotes from the data. For the dates which are in string format convert to appropriate date format. Conclude by selecting only the required coloumn for final output display.


Solution 2 (pandas):

![image](https://github.com/ShamleeBhoi/Alteryx/assets/162983736/c805201e-ceef-43ab-8a1c-64b6c992c1e7)

![image](https://github.com/ShamleeBhoi/Alteryx/assets/162983736/404444b5-dab2-47f9-8585-fcdf91e632b6)

The same results can be obtained using the str.split and str.strip functions to split the data into separate coloumns and removing quotes from text. The to_datetime is used to convert text into date format. 

