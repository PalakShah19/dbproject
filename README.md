# PostgreSQL Transaction Executor

This Python script demonstrates how to execute a series of SQL queries as atomic transactions using PostgreSQL and the psycopg2 library.

## Features

- Adds, renames, and deletes data in Product, Depot, and Stock tables.
- Ensures data integrity with transactions (commit/rollback).
- Uses environment variables for secure database connection.

## Requirements

- Python 3.x
- psycopg2 library
- A PostgreSQL database with tables: Product, Depot, Stock.

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/postgres-transaction-executor.git 
