PROJECT Goal:
Create a Bash script that enters information from World Cup games.csv file into PostgreSQL, then query the database for useful statistics.
Project made as part of the FreeCodeCamp Relational Databases Beta Certificate course


Dataset: games.csv

Created the database, 'worldcup', and the appropriate tables ('teams' and 'games') on PostgreSQL to visualise the data from games.csv.
Added appropriate constraints (primary keys and foreign keys) required to relate the tables.


Created a Bash script that reads the games.csv data and uses SQL query commands to insert the data automatically into the tables previously created.
Took constraints into consideration when creating the Bash script to insert all winner and opponent teams individually into 'teams' and then into 'games' based on the team_id created.

View: insert_data.sh
