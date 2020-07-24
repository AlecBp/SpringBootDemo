# Simple Spring Boot Demo
This demo covers the very basics of how to create a RESTful API with Spring Boot.
## PostgreSQL connection configuration
Inside of the project folder go to: src/main/resources/application.yml
Change the values inside of the application.yml so that it suits your database connection.
## Simply build the project with Maven and run it
The app will be available at [localhost:8080](localhost:8080)
## API endpoints
Method  | Endpoint          | Description                   | Request Body Example  |
--------|-------------------|-------------------------------|-----------------------|
GET     |api/v1/person      |returns all people             |                       |
GET     |api/v1/person/{id} |returns the person with id     |                       |
POST    |api/v1/person      |adds a person to the database  |{  "name": "John Doe"} |
PUT     |api/v1/person/{id} |updates person with id         |{  "name": "New Name"} |
DELETE  |api/v1/person/{id} |deletes person with id         |                       |