# Backend Readme

Make a short briefing

## Description of the Project

List the features or link to your WIKI page

- [ ]  Feature 1
- [ ]  Feature 2

### Set Up

- Data Base Setup
- Other requirement. (like redis)
- Install and run the project
- Installation troubleshooting (Typical errors that can happen)

### Run

- How to run the projects

- Other commands and their use. (Document the commands in your package.json or of your Laravel command line)

## Deployment

Notes for deployment, or brief about the pipeline configurations

URL of the existing environments
### Stack

What main libraries are used, with a link to the documentation. (I'm not talking about all the dependencies, but I am talking about the most important 3rd parties)

- Database
- Migrations
- Crons
- Queues
- Api Documentation
- Log library
- Sockets
- etc

## Architecture

### Database

Description of the database: 

It can be a diagram, but diagrams are hard to keep and doesn't explain important things.

I prefer to have a list of blocks of tables related, explained the relations and the dependencies.
Understanding the database is key to getting the business logic of the project.

For example

-----
Users: Basic User tables
User Session: (userId -> User) Sessions for authentication.
User Todo List: (userId -> User) A user can have a todo list of items, with the status done or not
-----

### File Structure

Which is the file structure

How to contribute if I need to do a new model -  controller.

## Logics

## Api Documentation

How we add the API documentation and generate it. (According to the library we using  like Swagger, scrible, etc)

### Queues

One short line for each feature that uses the queuing or events system.
These are things that if not put here are super difficult to see since they are not obvious in the back.d

### Schedules

A short line for each feature that uses the cron or schedules system.
These are things that, if not put here, are super difficult to see since they are not obvious in the backend.

### Env

Which environmental variables we have, what are their use, were are the secrets saved (without the credentials to them)

### Sockets

If is not included in your API describe the sockets actions and structure.

- Verification
- Request and Response Objects
- Existing Logics
- How to contribute

## Integrations

Integrations with 3erd parties and external services.

