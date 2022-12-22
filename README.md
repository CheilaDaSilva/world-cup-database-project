# 💻 Project: WorldCup Database 

![Worldcup banner](https://user-images.githubusercontent.com/88495091/209214406-b8edaa34-cc50-4e5b-b5f6-1312d845f3a4.png)


## Project goal: 
Create a Bash script that enters information from World Cup games.csv file into PostgreSQL, then query the database for useful statistics.

## Creating the database

Created the database, 'worldcup', and the appropriate tables ('teams' and 'games') on PostgreSQL to visualise the data from games.csv.
Added appropriate constraints (primary keys and foreign keys) required to relate the tables.

Table 'games' tracks all matches and shows scores made by winner and oponnent teams (using team_id as identifier for both).
Table 'teams' lists all teams that played, whether they were the winner team or the opponent team.

View: add link

### Relational Database diagram
![worldcup diagram](https://user-images.githubusercontent.com/88495091/209214872-dd4c465a-c8db-48b6-87fd-92f73b932ebc.PNG)

## Automating data insertion and querying with SQL
Created a Bash script that reads the games.csv data and uses SQL query commands to insert the data automatically into the tables previously created.
Took these constraints into consideration when creating the Bash script to insert all winner and opponent teams individually into 'teams' and then into 'games' based on the team_id created.

-Utilized SQL to query the database and obtain useful values.
Took these constraints into consideration when creating the Bash script to insert data



Steps taken:
- Created a database called worldcup and appropriate tables (called "teams" and "games") to visualise the data from games.csv, taking in account any primary keys and foreign keys required to relate the tables.
- Created a Bash script that reads the csv data and uses SQL query commands to insert the data automatically into the tables previously created.
- Utilized SQL to query the database and obtain useful values.


