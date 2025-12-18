**Chapter 17 Exercises**
These exercises are prtice using Bid Data. I use a database called books and a sql called books.

I use the sqlite3 cursor execute method to gather data from a table in the books database. I then 
use description and fetchall to display the data in a table format

I also use the books database to:
* Select all the authors last names from the authors table in decending 
order
* Select all the book titles from the titles table in ascending order
* Use INNER JOIN to selectall the books from a specific author(including the title, copyright year, and ISBN-alphabetically by
 title).
* Insert a new author into the authors table.
* Insert a new title for an author(new book will also have entry in the author_ISBN table and the titles
  table)
