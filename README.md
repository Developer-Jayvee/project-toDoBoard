# To-do Board Application

A full-stack task management application with Laravel backend and frontend interface.

## Project Structure
projet-toDoBoard/
├── frontend/
│ └── To-do-Board/ # Frontend application
├── backend/
│ └── To-do-Board-be/ # Backend Laravel application
└── docker-compose.yml # Docker configuration


## Prerequisites

Before you begin, ensure you have the following installed on your system:
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- Git

## Installation Guide

### 1. Clone the Repositories

First, create the project directory and clone both repositories inside it with the proper structure:

```bash
# Create project directory
cd projet-toDoBoard

# Create frontend and backend directories
mkdir frontend backend

# Clone frontend repository into frontend directory
git clone git@github.com:Developer-Jayvee/To-do-Board.git frontend/To-do-Board

# Clone backend repository into backend directory
git clone git@github.com:Developer-Jayvee/To-do-Board-be.git backend/To-do-Board-be
```
# Commands
Then run this commmand synchronously
```bash

# build
docker compose up --build

# Open backend container
docker compose exec backend bash

# Run this command in order
php artisan passport:install

# Set the name to 'ToDoBoard_App'
php artisan passport:client --personal 

php artisan migrate

php artisan key:generate 

php artisan db:seed --class=CategorySeed

php artisan queue:work
```

# Service	URL
- API Endpoint	http://localhost:8080/api/v1/
- Frontend Application	http://localhost:5173
- Postman Collection and Environment https://www.dropbox.com/scl/fo/1irpy2qarc24extkzo0nm/AOvdioShPi1XtSU6yPopj_I?rlkey=ohazpy39mtufpfm4udtqr3y88&st=r4tkbqh1&dl=0
