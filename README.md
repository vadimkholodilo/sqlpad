# SQLPad

A web app for writing and running SQL queries and visualizing the results. Supports Postgres, MySQL, SQL Server, ClickHouse, Crate, Vertica, Trino, Presto, SAP HANA, Cassandra, Google BigQuery, SQLite, TiDB and many more via ODBC.

![SQLPad Query Editor](https://user-images.githubusercontent.com/303966/99915755-32f78e80-2ccb-11eb-9f74-b18846d6108d.png)

## Project Status

This fork is not just a clone, it's an evolution. We are actively developing and infusing it with advanced AI capabilities. Our vision is to make SQLPad not just a tool for running SQL queries, but a comprehensive platform that can explain SQL queries and translate natural language to SQL. We are leveraging the power of Chat GPT and a custom self-hosted model to make this vision a reality. Stay tuned for a more intuitive, more intelligent SQLPad.

## Docker Image

The docker image runs on port 3000 and uses `/var/lib/sqlpad` for the embedded database directory.

See [docker-examples](https://github.com/vadimkholodilo/sqlpad/tree/master/docker-examples) for docker-compose examples.

## Project Documentation

There is no updated documentation website at the moment. However, you can still visit the
Old documentation located at [https://getsqlpad.com](https://getsqlpad.com).

## Development

For instructions on installing/running SQLPad from git repo see [DEVELOPER-GUIDE.md](https://github.com/sqlpad/sqlpad/blob/master/DEVELOPER-GUIDE.md)

## License

MIT
