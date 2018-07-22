---
title: "Printer Toner Inventory System"
excerpt: "Python program using web-scraping, Excel manipulation, sqlite3, and email libraries."
collection: portfolio
---
 
This is a program that I wrote to help automate a job in our department that was being done by hand every week. This program is written in Python and uses web-scraping libraries to retrieve the toner levels of all the printers in our division using the printer's web interface. This scraped data is then cleaned up and inserted into a database using SQL code. After the data is added to the database, another module of the program grabs the relevant data that is needed and inserts it into an excel spreadsheet in the format that is required by the department head. Once all of this is completed, an email is sent with a report of the process including any errors that could have occurred when the server ran the program.
