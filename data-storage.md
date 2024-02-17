# Architecture Decision Record: Data Storage

## Status

Proposed

## Context

The app requires a database that can store user orders, allowing users to quickly view and reorder prior transactions. This will promote user engagement within the app, and increase the probability that they will continue to use the app for future transactions.

## Decision

The app will use an Oracle database to store order history.

## Rationale

- **Expertise** : The development team has extensive knowledge of Oracle through their studies and personal use. As Oracle is a widely used database solution, there are sufficient resources available to the team should they require support.
- **SQL Functionality** : Oracle supports the use of SQL, which provides security, scalability, and data integrity to relational databases. It will also easily integrate with Python, the proposed backend language.
- **Scalability** : Oracle databases are able to query large datasets, which will be beneficial as the app grows.

## Consequences

The development team will need to devote a reasonable amount of time in further learning PL/SQL, as the use of the database becomes more complex.

Using Oracle will require compliance with their licensing agreements, which will need to be thoroughly reviewed by the development team. As well, understanding the pricing of the licensing structure will require a feasibility assessment.
