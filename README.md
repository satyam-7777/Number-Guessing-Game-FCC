# Build a Number Guessing Game

A PostgreSQL and Bash scripting project completed as part of the **freeCodeCamp Relational Database Certification**.

## Project Overview

This project involves creating an interactive number guessing game using **Bash** and **PostgreSQL**.

The program is designed to run in the terminal and allows users to guess a randomly generated number. It also stores user information and game statistics in a PostgreSQL database.

## Technologies Used

- PostgreSQL
- SQL
- Bash
- Git
- GitHub

## Database Structure

The database contains information related to the number guessing game, including:

- Users
- Games
- Game attempts
- User game statistics

The tables are related using PostgreSQL primary and foreign keys to represent relationships between users and their games.

## Number Guessing Game

The `number_guess.sh` Bash program provides an interactive interface for playing the number guessing game.

The program allows users to:

- Enter their username
- Generate a random secret number
- Make guesses through the terminal
- Receive feedback about their guesses
- Track the number of guesses made
- Store user and game information in the PostgreSQL database

The program uses PostgreSQL queries to retrieve existing user information and save game statistics.

## Project Requirements

The project was completed according to the freeCodeCamp requirements.

The project had to:

- Use PostgreSQL
- Create the required database tables
- Include primary keys
- Include foreign keys where required
- Store user information
- Store game information
- Create an interactive Bash program
- Connect the Bash program with PostgreSQL
- Generate and process number guesses
- Track the number of attempts
- Save user and game information in the database
- Pass all project tests
- Export the completed database as `number_guess.sql`
- Save the completed `number_guess.sh` file
- Submit the project through a public GitHub repository

## Project Files

The main project files are:

```text
number_guess.sql
number_guess.sh
