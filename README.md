# Demo postgresql

This repository provides a basic sample to activate postgresql pg_stat_statements module, mandatory to run with pgAssistant in a docker environment.

When the DB is up, connect to the DB and launch this SQL command to activate pg_stat_statements :

```
CREATE EXTENSION IF NOT EXISTS pg_stat_statements;
```

The sample also provides parameters that you should define by using the tool PGTune to optimize your postgresql database(https://pgtune.leopard.in.ua/).
Here with a 2GB and 4 CPU database.
