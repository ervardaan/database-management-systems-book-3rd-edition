# running sql queries

- loading in files to create a database
  - create a load.txt file to load all 15 tables from their text files
  - we already have database sql file
      - create a database using this command
          `sqlite3 CHAPTER5_DATABASE.db < dbbook.sql`
      - load the content into database using load file
          `sqlite3 CHAPTER5_DATABASE.db < load.txt`
  - we have created a makefile-run `make clean` and then `make` to just run this makefile(it contains all of these above 2 commands and cleaning of previous database)
- start jupyter notebook in the directory in which the queries reside
- then run the sql query file in jupyter notebook(CREATE A NEW IPYTHON NOTEBOOK FOR USING THE DATABASE)
- using oracle databases
    - download oracle client
    - download sqsplus
    - download odbc
    - extract all and add their directory to path variable in environment variables
    - install microsoft visual studio code 2022
    - 
