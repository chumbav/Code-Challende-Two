# week-2-code-challenge_phase-4
Superhero Powers API
Welcome to the Superhero Powers API! This API allows you to manage superheroes and their superpowers. It provides endpoints for creating, retrieving, updating, and deleting superheroes and powers, as well as establishing relationships between them.

# Setup
To get started with the Superhero Powers API, follow these steps:

Clone the repository to your local machine.
Install the required dependencies.
Set up your database and configure the connection details in the project's configuration file.
Run the database migrations to create the necessary tables.
(Optional) Generate seed data to populate the database with initial superheroes and powers.
Start the API server.
Congratulations! You have successfully set up the Superhero Powers API.

# Endpoints
The Superhero Powers API provides the following endpoints:

## Heroes
GET /heroes: Retrieves a list of all superheroes.
GET /heroes/:id: Retrieves a specific superhero by ID.
POST /heroes: Creates a new superhero.
PUT /heroes/:id: Updates an existing superhero.
DELETE /heroes/:id: Deletes a superhero.
## Powers
GET /powers: Retrieves a list of all superpowers.
GET /powers/:id: Retrieves a specific superpower by ID.
POST /powers: Creates a new superpower.
PUT /powers/:id: Updates an existing superpower.
DELETE /powers/:id: Deletes a superpower.
## Relationships
POST /hero_powers: Creates a new relationship between a superhero and a superpower.
Please note that the API returns data in JSON format and expects requests to be made with the appropriate HTTP verbs.

Feel free to explore and interact with the Superhero Powers API using these endpoints to manage superheroes, superpowers, and their relationships. Enjoy!
