Calculate the aggregate loan amount from a CSV file.

The programming language I picked is C# 
I used Visual Studio 2010 with windows forms components. I went with this selection because I am comfortable with these tools and use them in my day to day operations.
The front is a basic page with a button to process.
I used hash table for this task, to help me identify the key and for Lookup efficiency
I catered for columns that might change positions later on.

Assumptions 
•	Loans.csv is stored in c:/temp
•	If there is no file available, it will  display a message 
•	This application could have catered for a few error handling. But I wanted to keep the project clean, simple and stick to the basic requirements  
•	Column names always stay the same

Some of the error handling to think of :
•	More fields sent than required
•	Invalid Characters
•	Missing values and fields
