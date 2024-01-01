# Enigma DB

Enigma DB is a versatile, lightweight database built on top of PostgreSQL, transforming your relational database into a powerful key-value store. This project is designed to provide a convenient and interactive interface, allowing users to interact with their database using simple commands through a Command Line Interface (CLI).

## Features

- **Interactive CLI**: Enigma DB comes with a user-friendly Command Line Interface that allows users to easily interact with their PostgreSQL database using basic commands.

- **Key-Value Storage**: Seamlessly utilize your PostgreSQL database as a key-value store. Enigma DB efficiently manages keys and their corresponding values, making it easy to store, retrieve, and manipulate data.

- **Sharding for Performance**: Enigma DB intelligently shards the data across two PostgreSQL servers, optimizing performance by distributing keys based on their initial letter.

- **CRON Job for Cleanup**: Keep your database clean and efficient with a CRON job that periodically deletes expired keys, ensuring optimal performance and resource utilization.

## Getting Started

To get started with Enigma DB, follow these simple steps:

### 1. Configure PostgreSQL URLs

Start two PostgreSQL servers and add the PostgreSQL URLs of your servers to the `env.ts` file.

### 2. Compile TypeScript

Run the TypeScript compiler to convert your TypeScript files to JavaScript.

```bash
tsc
```

## 3. Run the Script

Launch Enigma DB in interactive mode to execute commands using the CLI.

```bash
node dist/src/interactive.js
```
