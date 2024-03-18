Exercise 2: 

Many products will export textual data with delimiters such as quotes.  This is done so that strings can contain delimiters or control characters within them.   Having more than one type of delimiter can be hard for ETL programs to interpret.  In the input text file, there are two different delimiters (double quotes, single quotes) and they surround different data types.
Use Alteryx to strip out the delimiters as superfluous and format the data as represented in the output

Solution 1:


![image](https://github.com/ShamleeBhoi/Alteryx/assets/162983736/e5b12c85-2c85-44f5-bb65-51283b572257)

Used the text-to-coloumn tool separate data from single field to delimiter based coloumn, then trim the " and ' quotes from the data. For the dates which are in string format convert to appropriate date format. Conclude by selecting only the required coloumn for final output display.
