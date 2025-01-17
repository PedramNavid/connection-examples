# Materialize connection examples

[![Slack Badge](https://img.shields.io/badge/Join%20us%20on%20Slack!-blueviolet?style=flat&logo=slack&link=https://materialize.com/s/chat)](https://materialize.com/s/chat)

[Materialize](https://github.com/MaterializeInc/materialize) is a streaming database for real-time applications. It is wire-compatible with PostgreSQL, which means that you can connect to a Materialize instance using your favorite client libraries, ORM frameworks and other third-party tools that support PostgreSQL.

This repo is a collection of reference examples for common language-specific PostgreSQL drivers and PostgreSQL-compatible ORMs that have been tested with Materialize.

## Client libraries and Frameworks

- [PHP](./php)
  - [Laravel](./laravel)
- [NodeJS](./nodejs)
  - [AdonisJS](./adonisjs)
- [Deno](./deno)
- [Java](./java)
- [Python](./python)
  - [FastAPI](./fastapi)
- [Ruby](./ruby)
- [Go](./go)

## Helpful resources:

* [`CREATE SOURCE`](https://materialize.com/docs/sql/create-source/) - syntax for creating new connections to upstream data sources.
* [`CREATE MATERIALIZED VIEW`](https://materialize.com/docs/sql/create-materialized-view/) - syntax for creating an incrementally updating materialized view.
* [`SELECT`](https://materialize.com/docs/sql/select) - syntax for querying materialized views.
* [`TAIL`](https://materialize.com/docs/sql/tail/) - syntax for subscribing to changes in a materialized view or query via a long-lived PostgreSQL transaction.
* [Materialize Demos](https://github.com/MaterializeInc/demos)

## Getting support

If you run into a snag or need support as you explore the examples in this repo, join the [Materialize Slack community](https://materialize.com/s/chat) or [open an issue](https://github.com/MaterializeInc/connection-examples/issues)!
