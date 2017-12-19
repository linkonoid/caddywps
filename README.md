# caddywinphpserver

Greetings to all PHP developers!

Today in an hour sketched a prototype of a Windows server based on the Caddy server for PHP-developers on OctoberCMS (Caddy server + PHP7 in FastCGI mode + OctoberCMS & Sqlite for storage this CMS). Assembly can also be used in production, works stably (this is Caddy & Golang!).

Installation - not required: extract archive (caddywinphpserver.zip + download parts caddywinphpserver.z01 caddywinphpserver.z02) and just run caddywinphpserver.exe!!! To go to the OctoberCMS Admin Panel select the top item of the program menu from the tray (admin/admin). In some cases (if not), use the hostseditor.exe utility (also launched from the tray menu) to register localhost (127.0.0.1) in the hosts file. Successful work!

The project includes 2 utilities from the winginx project (hostseditor.exe and php-config.exe).

P.S. This is an assembly for Win64. It is also possible to add support for Win32, MySQL, Redis, Node etc. (15 minutes of work).
