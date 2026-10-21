## Tarantool Testcontainers Module

This project contains the implementation of the `testcontainers` module for `Tarantool`.

Supported usage scenarios:

| Name                | Product Version                                            |
|---------------------|------------------------------------------------------------|
| Single Tarantool Node | <ul><li>[x] 3.x </li><li>[ ] 2.11.x</li></ul>              |
| TDB Cluster         | <ul><li>[x] 3.x </li><li>[x] 2.x</li><li>[ ] 1.x</li></ul> |
| TQE Cluster         | <ul><li>[x] 2.x </li><li>[ ] 3.x</li></ul>                 |

### Architecture

Information about the module architecture can be found:

* [Architecture of "Single Tarantool Node" solution](../documentation/doc-src/pages/testcontainers/single/single-node-testcontainers-arch.en.md)
* [Architecture of "TDB Cluster" solution](../documentation/doc-src/pages/testcontainers/tdb/tdb-cluster-testcontainers-arch.en.md)
* [Architecture of "TQE Cluster" solution](../documentation/doc-src/pages/testcontainers/tqe/tqe-cluster-arch.en.md)

### Usage Examples

Usage examples of the module can be found:

* [Example of using testcontainers for a single Tarantool node](../documentation/doc-src/pages/testcontainers/single/single-node-testcontainers-standard-impl-example.en.md)
* [Example of using testcontainers for a TDB cluster](../documentation/doc-src/pages/testcontainers/tdb/tdb2-cluster-testcontainers-standard-impl-example.en.md)
* [Example of using testcontainers for a TQE cluster](../documentation/doc-src/pages/testcontainers/tqe/tqe-cluster-example.en.md)
