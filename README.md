codeally@0aa4eb30dce3:~/project$ psql --username=freecodecamp --dbname=postgres;
Border style is 2.
Pager usage is off.
psql (12.9 (Ubuntu 12.9-2.pgdg20.04+1))
Type "help" for help.

postgres=> \c universe
You are now connected to database "universe" as user "freecodecamp".
universe=> \d
              List of relations
+--------+-----------+-------+--------------+
| Schema |   Name    | Type  |    Owner     |
+--------+-----------+-------+--------------+
| public | galaxy    | table | freecodecamp |
| public | moon      | table | freecodecamp |
| public | more_info | table | freecodecamp |
| public | planet    | table | freecodecamp |
| public | star      | table | freecodecamp |
+--------+-----------+-------+--------------+
(5 rows)

universe=> SELECT * FROM galaxy,
universe-> hhjghg
universe-> SELECT * FROM galaxy;
FATAL:  terminating connection due to administrator command
server closed the connection unexpectedly
        This probably means the server terminated abnormally
        before or while processing the request.
The connection to the server was lost. Attempting reset: Succeeded.
universe=> SELECT * FROM moon;
