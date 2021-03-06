# Version 3.0.3
- Add support Python 3.
- Control error in importing modules.

# Version 3.0.2
- Add option overwrite in _save_json, _mysql_database_json_update.
- Add progressbar in _fix_insert_read_mysql.
- Move _mysql_database_json_update to the start of main().

# Version 3.0.1
## FIX:
- Control table content `__EFMigrationsHistory`.
  
# Version 3.0.0
- Add support to automatically export the data to the mysql server.
- Check that the data has been successfully exported.
- Update `database.json` with the data that we specify.

# Version 2.0.0
- Read the file `databse.json` and search for databases of type sqlite.
- We eliminate the need for external sqlite3 program, now from python we read sqlite databases.
- The generated inserts are no longer printed directly on the screen, they are now saved in a file.
- The tables are sorted so that the inserts are generated in a correct order and when inserting no of related table errors.

# Version 1.0.0
- Dump database SQLite and convert to format MySQL.