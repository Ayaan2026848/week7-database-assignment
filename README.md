# Week 7 Database Assignment

## Topic
Audit Logging, Category Trees, and Safe Migrations

## Database
PostgreSQL 18.6

## Assignment Tasks

1. Create an audit log table and trigger function.
2. Test audit logging using UPDATE and DELETE operations.
3. Create a self-referencing categories table and use a recursive CTE.
4. Prepare versioned database migration files using Flyway naming conventions.
5. Create database roles and apply permissions following the principle of least privilege.

## Migration Files

- `V1__core_tables.sql` — Core tables
- `V2__audit_log.sql` — Audit logging
- `V3__categories.sql` — Category tree

## Status
SQL objects and security roles have been created and checked. Flyway migration execution and migration history verification still need to be completed.