## Awesome ScyllaDB Projects

A curated list of awesome ScyllaDB projects, libraries, and tools in various programming languages. ScyllaDB is a high-performance NoSQL data store compatible with Apache Cassandra, known for its low-latency and high-throughput performance.

### General

- **[ScyllaDB](https://github.com/scylladb/scylladb)**: The main repository for ScyllaDB, a high-performance NoSQL data store compatible with Apache Cassandra. It utilizes the Seastar framework to deliver low-latency and high-throughput performance​ ([GitHub](https://github.com/scylladb/scylladb))​.

## Drivers and Libraries

### Go

- **[GocqlX](https://github.com/scylladb/gocqlx)**: A comprehensive Go library for ScyllaDB and Cassandra, featuring CQL query building, ORM functionalities, and migration tools. It simplifies data binding and query execution​ ([GitHub](https://github.com/scylladb/gocqlx))​.
- **[Scylla Go Driver](https://github.com/scylladb/scylla-go-driver)**: An experimental, high-performance Go driver created by students at the University of Warsaw. It supports token-aware and shard-aware routing, prepared statements, and compression​ ([GitHub](https://github.com/scylladb/scylla-go-driver))​.

### Rust

- **[Scylla Rust Driver](https://github.com/scylladb/scylla-rust-driver)**: An asynchronous CQL driver optimized for ScyllaDB. It includes features such as token-aware routing, shard-aware routing, and prepared statements​ ([GitHub](https://github.com/scylladb/scylla-rust-driver))​.
- **[Charybdis](https://github.com/nodecosmos/charybdis)**: A Rust ORM for ScyllaDB and Apache Cassandra. It supports automatic migration generation, insertion, and querying of data, making it easier to interact with ScyllaDB in a Rust application​ ([GitHub](https://github.com/nodecosmos/charybdis))​.
- **[Rust S3 ScyllaDB](https://github.com/javiramos1/rust-s3-scylladb)**: This project provides a real-world example of integrating AWS S3 and ScyllaDB using Rust. It demonstrates how to create ultra-fast REST APIs with Actix Web, manage credentials, ingest data from S3 into ScyllaDB, and perform graph data modeling for fast traversals​ ([GitHub](https://github.com/javiramos1/rust-s3-scylladb))​.
- **[Scylla Rust UDF](https://github.com/scylladb/scylla-rust-udf)**: A helper library for writing user-defined functions (UDFs) in pure Rust for ScyllaDB. It allows developers to write UDFs that are compiled to WebAssembly (Wasm) and used within ScyllaDB, although it is still an experimental feature​ ([GitHub](https://github.com/scylladb/scylla-rust-udf))​.

### PHP

- **[scylladb-php-driver](https://github.com/he4rt/scylladb-php-driver)**: A modern, feature-rich PHP client library for ScyllaDB and Apache Cassandra, utilizing Cassandra's binary protocol. It supports PHP 8.1 and 8.2, and offers features like shard-aware routing, support for various CQL data types, and async query execution. The driver can be installed from source or using Docker for testing environments​ ([GitHub](https://github.com/he4rt/scylladb-php-driver))​​.
- **[ScyllaDB Alternator PHP Example](https://cloud-getting-started.scylladb.com/stable/alternator/build-with-php.html)**: This example demonstrates how to use the AWS SDK for PHP to interact with ScyllaDB's Alternator, a DynamoDB-compatible API. It includes examples of creating tables, adding items, listing items, and deleting items in ScyllaDB using PHP​ ([ScyllaDB Getting Started](https://cloud-getting-started.scylladb.com/stable/alternator/build-with-php.html))​.

### JavaScript

- **[ScyllaDB Driver for Node.js](https://github.com/expressots/scylladb-driver)**: A modern, fully-featured ScyllaDB driver for Node.js and TypeScript. This driver supports synchronous and asynchronous operations, connection to ScyllaDB clusters, query execution, load balancing policies, retry policies, speculative execution, metrics, logging, and schema inspection. It is designed to work with Node.js versions 18.x and above​ ([GitHub](https://github.com/expressots/scylladb-driver))​.
- **[Getting Started with ScyllaDB Cloud Using Node.js](https://www.scylladb.com/2023/03/02/getting-started-with-scylladb-cloud-using-node-js-part-1/)**: A step-by-step guide to building a simple Node.js application with ScyllaDB Cloud. The tutorial covers setting up the environment, creating a cluster, connecting to the cluster, and performing CRUD operations using JavaScript​ ([ScyllaDB](https://www.scylladb.com/2023/03/02/getting-started-with-scylladb-cloud-using-node-js-part-1/))​.
- **[IoT App with JavaScript](https://iot.scylladb.com/stable/build-with-javascript.html)**: This tutorial demonstrates building an IoT application that uses ScyllaDB as the backend database. It includes instructions on setting up the database schema, simulating sensor data, and periodically saving data to the database using Node.js​ ([ScyllaDB IoT](https://iot.scylladb.com/stable/build-with-javascript.html))​.

### Python

- **[ScyllaDB Driver for Python](https://github.com/scylladb/python-driver)**: A modern, feature-rich and highly-tunable Python client library for Scylla Open Source (2.1+) and Apache Cassandra (2.1+) and Scylla Enterprise (2018.1.x+) using exclusively Cassandra's binary protocol and Cassandra Query Language v3. This driver supports Python versions 3.6-3.11.
- **[Getting Started with ScyllaDB Cloud Using Python](https://cloud-getting-started.scylladb.com/stable/build-with-python.html)**: A step-by-step guide to building a simple Python application with ScyllaDB Cloud. The tutorial covers setting up the environment, creating a cluster, connecting to the cluster, and performing CRUD operations using Python.
- **[Scylla cqlsh](https://github.com/scylladb/scylla-cqlsh)**: Command line tool to connect to ScyllaDB (or Apache Cassandra). A fork of the cqlsh tool from https://github.com/apache/cassandra.

## Documentation Tools

### Sphinx

- **[Sphinx ScyllaDB Theme](https://github.com/scylladb/sphinx-scylladb-theme)**: A documentation toolchain for ScyllaDB projects that provides a consistent look and feel across all documentation sites. It supports multi-version documentation and GitHub Pages integration​ ([GitHub](https://github.com/scylladb/sphinx-scylladb-theme))​.
