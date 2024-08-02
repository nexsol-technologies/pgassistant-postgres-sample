# Demo postgresql

This repository provides a basic sample to activate postgresql pg_stat_statements module, mandatory to run with pgAssistant in a docker environment.

When the DB is up, connect to the DB and launch this SQL command to activate pg_stat_statements :

```
CREATE EXTENSION IF NOT EXISTS pg_stat_statements;
```
