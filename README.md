# How-to-show-all-process-is-connecting-to-mysql
How to show all process is connecting to mysql

<div class="markdown prose w-full break-words dark:prose-invert light">

You can use the following command to view all the processes that are currently connected to your MySQL server:

<pre>

<div class="bg-black mb-4 rounded-md">

<div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans"><span class="">sql</span><button class="flex ml-auto gap-2">Copy code</button></div>

<div class="p-4 overflow-y-auto">`<span class="hljs-keyword">SHOW</span> PROCESSLIST;` </div>

</div>

</pre>

This command will display a list of all the current connections to your MySQL server, including the user, host, database, command, time, and state of each process. The output will also show you the process ID (PID) of each connection, which you can use to terminate a specific process if needed.

If you want to see more detailed information about a particular process, you can use the `SHOW FULL PROCESSLIST` command instead. This command will display additional information about each process, such as the query being executed and the number of rows affected.

Note that you need to have the necessary privileges to execute these commands, so make sure you're logged in as a user with sufficient permissions to view the process list.

</div>
