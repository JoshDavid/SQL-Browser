# SQL Browser
Simple database browser for ODBC compliant databases. Currently designed for Windows, but a cross platform app could be released in future versions. 

Dyalog APL comes with a powerful SQL interface. New users who don't want to read the docs to get it working, or older users who are tired of trying to remember table/column names will find this tool useful. Get your work done quick with the assistance of this browser, and let it take care of securely handling your database credentials. 

This library requires EasyGUI as a dependency. If you use Dado, or some other package manager, it will fetch EasyGUI for you. Otherwise, you must load the EasyGUI namespace yourself as a sibling namespace to DBViewer. 

If you use Dado:
`]Dado.openproject C:\Git\SQL-Browser`

If you use Link:
`]link.create #.DBViewer C:\Git\SQL-Browser\APLSource`
`]link.create #.EasyGUI C:\Git\EasyGUI\APLSource`

Then just Run the application:
`DBViewer.Run`

Tested with PostgreSQL, Oracle, and SQL-Server.

Currently in Beta. Feel free to download and play around with it, but an official release may not be backwards-compatible with Beta versions.
