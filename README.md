# Events API

A minimal REST API for managing events built with GoLang.

## Features

- Signup, Login
- Create, Update, Get, Delete event
- Validation with custom error handling

## Quick Start

- Installed Golang: https://go.dev/doc/install  

## Local Development Workflow

- To run source code: `go run main.go`  
- To compile bin file: `go build -o bin/binFileName`  
- To run compiled bin file: `./bin/binFileName`  
- Signup -> Login (Get a token) -> Work with events

## API endpoints

| Method |       Endpoint       |     Description     |
|:------:|----------------------|---------------------|
| POST   | /events              | Create event        |
| GET    | /events              | Get all events      |
| GET    | /events/:id          | Geg event by ID     |
| DELETE | /events/:id          | Delete event by ID  |
| PUT    | /events/:id          | Update event by ID  |
| POST   | /events/:id/register | Register to event   |
| DELETE | /events/:id/register | Cancel registration |
| POST   | /signup              | Signup              |
| POST   | /login               | Login               |

## Requests examples

Could be found in `api-test/` directory  

## License

This project is for educational/demonstration purposes. 
Production usage would require additional features like database persistence, 
authentication, and more comprehensive error handling.