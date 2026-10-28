# DCIT 26 Lab 5: Express and MongoDB

Student Records REST API using Node.js, Express, MongoDB, and Mongoose.

## Setup
1. Clone the repo and run `npm install`
2. Copy `.env.example` to `.env`

## MongoDB Configuration
Install MongoDB locally and make sure it is running. Set in `.env`:
MONGODB_URI=mongodb://127.0.0.1:27017/lab5_students
PORT=5000

## Run the Server
npm run dev      (development, with nodemon)
npm start        (production)

## API Routes
| Method | Route | Description |
|---|---|---|
| GET | /api/health | Health check |
| GET | /api/students | Get all students |
| GET | /api/students/:id | Get one student (404 if missing) |
| POST | /api/students | Create a student (201) |
| PUT | /api/students/:id | Update a student |
| DELETE | /api/students/:id | Delete a student |