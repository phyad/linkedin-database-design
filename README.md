# LinkedIn Database Design

## Project Overview

This project involves designing a relational database for a LinkedIn-style professional networking platform using SQLite.

The database was designed from scratch to represent users, schools and universities, companies, professional connections, education history, and employment history.

## Project Objectives

The database was designed to support:

* User profiles and authentication information
* Schools and universities
* Companies and their industries
* Mutual connections between users
* Users' educational affiliations
* Users' employment history
* Current and previous relationships between users and organizations

## Database Structure

The database consists of six related tables:

* **Users** — stores users' names, usernames, and passwords.
* **Schools** — stores school and university information.
* **Companies** — stores company information and industries.
* **Connections** — represents mutual connections between users.
* **Education** — links users to schools and records their degree and attendance period.
* **Employment** — links users to companies and records their job title and employment period.

## SQL Concepts Demonstrated

* Relational database design
* Primary keys
* Composite primary keys
* Foreign keys
* UNIQUE constraints
* NOT NULL constraints
* Table relationships
* Many-to-many relationship design
* Database normalization concepts
* SQLite

## Database Relationships

The database uses foreign keys to establish relationships between users and their educational and professional affiliations.

The `connections` table also uses two foreign keys referencing the `users` table to represent relationships between users.

The `education` and `employment` tables use composite primary keys to allow a user to have multiple educational or employment records while maintaining record uniqueness.

## Outcome

The project demonstrates the ability to translate real-world platform requirements into a structured relational database design using SQL and SQLite.
