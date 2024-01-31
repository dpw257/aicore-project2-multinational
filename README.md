# Project title: Multinational Retail Data Centralisation
Data extraction, data cleaning and running SQL queries


## Description of the project
A database was compiled from different files types, extracted from AWS servers using various methods.
Functions were defined for cleaning the data as Pandas dataframes based on specific issues found and the data was saved to a local SQL database. A starbased schema was created for the database by defining primary and foreign keys, and SQL queries were run using Python.


## Installation instructions
Download files and run code_main.py to extract, clean and save the data to a local SQL database (PostgreSQL).
A YAML file named db_creds.yaml with credentials is also required to extract the data files from the AWS server. The YAML file also contains credentials for accessing the local SQL database.

# Usage information
The files should be ran in the following order:
main_code.py - to extract, clean and save the data
sql_starbased.py - to create a starbased schema for the database, add further columns and define data types in columns
sql_queries.py - to run defined SQL queries on data

## License information
MIT License

Copyright (c) [2024] [Daniel White]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
