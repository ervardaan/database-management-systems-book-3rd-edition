# running sql queries

- loading in files to create a database
  - create a load.txt file to load all 15 tables from their text files
  - we already have database sql file
      - create a database using this command
          `sqlite3 CHAPTER5_DATABASE.db < dbbook.sql`
      - load the content into database using load file
          `sqlite3 CHAPTER5_DATABASE.db < load.txt`
- start jupyter notebook in the directory in which the queries reside
- then run the sql query file in jupyter notebook(CREATE A NEW IPYTHON NOTEBOOK FOR USING THE DATABASE)
