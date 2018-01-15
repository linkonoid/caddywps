# caddywinphpserver

Greetings to all PHP developers!

Windows PHP-server based on the Caddy server for PHP-developers on OctoberCMS (Caddy server + PHP7 in FastCGI mode + OctoberCMS & Sqlite for storage this CMS + free admins components). Assembly can also be used in production, works stably (this is Caddy & Golang!). 
Includes components:
- Caddy server
- PHP 7.1.1
- 2 utilities from the winginx project (hostseditor.exe and php-config.exe)
- HeidiSQL for MySQL, PostgreSQL, Miqrosoft SQL Server administration
- SQLite Administrator
- WinSCP for remote SSH
- Sendmail dummy for debugging the sending of emails

Download archive: http://caddywps.linkonoid.com/download
Installation - not required: extract archive and just run caddywps.exe!!! To go to the OctoberCMS Admin Panel select the top item of the program menu from the tray (admin/admin) or new installation.
!!!In some cases (if not), use the hostseditor.exe utility (also launched from the tray menu) to register localhost (127.0.0.1) in the hosts file. Successful work!
