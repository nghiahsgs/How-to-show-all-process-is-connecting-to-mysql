# How-to-show-all-process-is-connecting-to-mysql
How to show all process is connecting to mysql

You can use the following command to view all the processes that are currently connected to your MySQL server:

```
SHOW PROCESSLIST;
```

This command will display a list of all the current connections to your MySQL server, including the user, host, database, command, time, and state of each process. The output will also show you the process ID (PID) of each connection, which you can use to terminate a specific process if needed.

If you want to see more detailed information about a particular process, you can use the `SHOW FULL PROCESSLIST` command instead. This command will display additional information about each process, such as the query being executed and the number of rows affected.

Note that you need to have the necessary privileges to execute these commands, so make sure you're logged in as a user with sufficient permissions to view the process list.
