# ADHOC-Battleship
Online battleship platform for PacificMUN 2020 ADHOC Committee

Live version can be found at: ~~http://adhoc.pacificmun.org~~ https://jaewuchun.com/pacificmun/adhoc

Pages it includes:
 - Log-in page (log in as either staff or delegate... login credentials are hard-coded since I had to rush coding the system. Not too bad because there are only 9 possible logins
 - Delegate/Agent portal page -- shows their stats (health, # of missiles, name, etc.) & battleship grid
 - Dais/Staff control panel page (shows all delegates, the grid, and includes function to change any delegates' stats)

Currently in Beta stage

There are quite a few lines of code that are not adequately optimized, as I was rushing its completion.

Database-y things:
 - One database (ADHOCY) with two tables (master, grid)
 - Master table contains information about the delegates and their stats
 - Grid table contains the battleship grid; A-J on the x axis, 1-10 on the y axis

Some context:
 - repo contains HTML, CSS, and PHP (+MySQL queries)
 - the file 'dbh.inc.php' merely connected the client to a database. It's been omitted from this repository because of sensitive information on it
