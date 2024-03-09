# About this project
Use the data set to study the number of candidates hired and do an in-depth
analysis, such as reading, cleaning and analyzing to obtain a result that is easily
interpretable through a Dashboard.

The main idea is to perform a solution with ETL to obtain a result on the data of the set.

# Needed tools
1. Docker
2. Pgadmin
3. PostgreSQL
4. Anaconda or other enviroment

# How it works
1. Execute the docker-compose and set the enviroment to set the DB and PG admin login:
  process.env:
  DATABASE_HOST=
  POSTGRES_USER=
  POSTGRES_PASSWORD=
  POSTGRES_DB=

  pgadmin.env:
  PGADMIN_DEFAULT_EMAIL: ""
  PGADMIN_DEFAULT_PASSWORD: ""
2. Set the csv_file_path = '/candidates.csv' in the nootebook
3. Execute the workshop1 file.

By Davele12, David Velasquez Lenis.
