This app is to generate payroll and expenses dates:

# Installation

- Run: `composer install`.
- Navigate to the root directory from your terminal and run:  
`./index run 2017`
- This will show the output on the console as a **table** and create a **csv** file on the root of the application, named by year and extension of `.txt`: For example: `2017.txt`.

.........

Company Ltd with many branches across Europe handle their sales payroll in the following way:

The normal base salaries are paid on the last day of the month unless that day is a Saturday or a Sunday (weekend); if this is the case they will be paid on the last working day of the month. 

On the 1st and 15th of each month the expenses are paid for the previous fortnight, unless those days are on a weekend, in which case they are paid on the first Monday after that date.

The company needs the output in the following format:

"Month Name", "1st expenses day", “2nd expenses day”, "Salary day" 

"January", "YYYY-MM-DD", "YYYY-MM-DD", "YYYY-MM-DD" 

"February", "YYYY-MM-DD", "YYYY-MM-DD", "YYYY-MM-DD" 
