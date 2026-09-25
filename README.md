# World Cup Database ⚽🏆

A PostgreSQL database and Bash scripting project to automatically import and analyze World Cup match data.

## Technologies Used
* **Bash Scripting:** File parsing (`while read` loops, variable extraction).
* **PostgreSQL:** Relational database management.
* **SQL:** Advanced querying (`JOIN`, aggregate functions).

## Project Structure
* `insert_data.sh`: Reads `games.csv` and dynamically inserts data into the `teams` and `games` tables.
* `queries.sh`: Executes complex SQL queries to extract tournament statistics.
* `games.csv`: Raw dataset.
