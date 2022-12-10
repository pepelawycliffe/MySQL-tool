# MySQL management tool

MySQL management tool  is a unified visual tool for database architects, developers, and DBAs. It provides various functionality for designing, developing, and administering databases. It’s available in 1 editions, Community editions. Community is a free open-source edition offering a basic set of features.

## Features

* Manage MySQL Connections (support SSL connection)
* List MySQL Servers
* List MySQL Tables
* List MySQL Databases
* List MySQL Columns
* Run MySQL Query



## Usage

 To add a MySQL connection, in the VS Code Explorer, click "MYSQL" in the bottom left corner, then click the 'Add' button, and then enter the host, user, password, port, and certificate file path (optional) in the input box.

 [connection](images/connection.png)

  * To run MySQL query, open a SQL file first then:
  * right click on the SQL file, then click `Run MySQL Query` in editor context menu (Note: you could also run the selected SQL query)
  * or use shortcut `Ctrl+Alt+E`
  * or press `F1` and then select/type `Run MySQL Query`

[run](images/run.png)

  * To create a new MySQL query or change active MySQL connection (You could see active MySQL connection in status bar):
  * right click on a MySQL server, then click `New Query`
  * or right click on a MySQL database, then click `New Query`

[newquery](images/newquery.png)


## Settings

* `MySQL tool.maxTableCount`: The maximum table count shown in the tree view. (Default is **500**)
* `MySQL tool.enableDelimiterOperator`: Enable support for DELIMITER operator. (Default is **true**)
