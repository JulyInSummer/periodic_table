# Periodic table
This is the simple project which interacts with PostgreSQL database with the help of bash script which prints the properties of chemical element from periodic table.

## Intallation
Clone this project to your local machine. You need your postgres running. Then run this command in your terminal to create a database and insert all the rows needed to play around with this project:

```
psql -U postgres < periodic_table.sql>
```

## Notes
This is relational databases certification project. There is no any input validation for now. The name of the project [Build a Periodic Table Database](https://www.freecodecamp.org/learn/relational-database/build-a-periodic-table-database-project/build-a-periodic-table-database) on [freeCodeCamp](https://www.freecodecamp.org)