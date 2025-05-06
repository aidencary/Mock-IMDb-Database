# Mock IMDb Database

This project is a **Mock IMDb Database**, built to simulate an IMDb-like database structure using manually inserted entries. It demonstrates database design principles, relational data modeling, and SQL queries for managing and interacting with movie and TV show data.

## Table of Contents

- [Features](#features)
- [Database Design](#database-design)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Example Queries](#example-queries)
- [Contributors](#contributors)
- [License](#license)

## Features

- **Relational Database Model**: Incorporates many-to-many and one-to-many relationships between key entities like Movies, TV Shows, Actors, Writers, and Directors.
- **Derived Attributes**: Includes views to calculate derived attributes such as age and average ratings.
- **Sample Data**: Preloaded with sample data for movies, TV shows, actors, writers, and directors.
- **Comprehensive Queries**: Supports complex queries to retrieve and analyze data, including average ratings, relationships, and attributes.

## Database Design

The database is designed around the following key entities:

1. **Movies**
   - Information about movies, including title, release date, runtime, description, age rating, and genres.
   - Relationships with actors, writers, directors, and streaming platforms.

2. **TV Shows**
   - Information about TV shows, including title, release date, description, age rating, and genres.
   - Relationships with episodes, actors, writers, directors, and streaming platforms.

3. **Actors**
   - Actor profiles, including biography, height, place of birth, awards, and relationships (parents, children, and media appearances).

4. **Writers and Directors**
   - Profiles for writers and directors, including biographical information, awards, and relationships with movies and TV shows.

5. **Derived Attributes**
   - Views for calculating average ratings and age for actors, writers, and directors.

## Technologies Used

- **Database**: Oracle SQL
- **Programming Language**: SQL
- **Tools**: SQL Developer or any database management tool supporting Oracle.

## Setup Instructions

To use this project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/aidencary/Mock-IMDb-Database.git

2. **Set Up the Database**:

- Use an Oracle SQL database to execute the provided SQL scripts.
Run the IMDb_Database.txt file to create tables, insert data, and set up relationships.

3. **Run Queries**:

- Use the example queries provided in the SQL script to retrieve and modify data.

**Contributors**:
- Aiden Cary
- Bradley Turnage
