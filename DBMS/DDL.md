# DDL commands:
https://www.educba.com/sql-ddl-commands/ <br>
https://www.sqlshack.com/sql-ddl-getting-started-with-sql-ddl-commands-in-sql-server/

# ALTER:
- https://www.studytonight.com/dbms/alter-query.php<br>
  alter command querries
- https://www.tutorialspoint.com/sql/sql-alter-command.htm <br>
  defination and type of alter.
- https://www.educba.com/sql-alter-command/ <br>
  everythng about alter in det.
- https://www.geeksforgeeks.org/sql-alter-add-drop-modify/
  (add,drop,modify)
  
# TRUNCATE
- https://www.geeksforgeeks.org/sql-drop-truncate/#:~:text=DROP%20is%20used%20to%20delete,database%20management%20system%20(RDBMS).<br>
  drop v/s truncate
- https://codingsight.com/rollback-truncate-in-sql-server/#:~:text=You%20cannot%20ROLLBACK%20TRUNCATE,still%20in%20the%20MDF%20file.<br>
  rollback a truncate in sql server(we cannot rollback a ddl command becasue they are implicitly precedded by a commit operation).
- https://www.tutorialspoint.com/sql/sql-truncate-table.htm<br>
  truncate in easy words.
- **Can we rollback delete and truncate?**<br>
  The operation cannot be rolled back. DROP and TRUNCATE are DDL commands, whereas DELETE is a DML command. 
  DELETE operations can be rolled back (undone), while DROP and TRUNCATE operations cannot be rolled back.
- **why delete can be rollback and truncate cannot**
  https://blog.sqlauthority.com/2007/12/26/sql-server-truncate-cant-be-rolled-back-using-log-files-after-transaction-session-is-closed/ <br>
- **Does truncate free space? **<br>
  Truncating a table does not give any free space back to the disk - you need to run a SHRINKDATABASE operation for the allocated space to be successfully de-allocated and returned to the disk.
- https://www.geeksforgeeks.org/difference-between-drop-and-truncate-in-sql/
  drop v/s truncate
  
