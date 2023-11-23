# Diary App Frontend

Welcome to the Diary App frontend repository! This part of the application is responsible for providing a user-friendly interface to manage your diary entries. Below, you'll find information on how to set up and use the frontend.

## Table of Contents

- [Getting Started](#getting-started)
  - [Installation](#installation)
- [Usage](#usage)
  - [Creating a Diary Entry](#creating-a-diary-entry)
  - [Viewing Diary Entries](#viewing-diary-entries)
  - [Updating Diary Entries](#updating-diary-entries)
  - [Deleting Diary Entries](#deleting-diary-entries)
  - [Searching for Entries](#searching-for-entries)
- [Technical Details](#technical-details)
  - [Dependencies](#dependencies)
  - [Project Structure](#project-structure)

## Getting Started



### Installation

1. Clone the repository.
2. Navigate to the frontend directory: `cd client`
3. Open index.html

## Usage

### Creating a Diary Entry

1. Open the Diary App in your browser.
2. Enter username. Eg. "john12"
3. Navigate to the "Create Entry" section.
3. Fill in the details for the date, time, text, and category.


### Viewing Diary Entries

1. Visit the "Diary Entries" section to see a list of all your entries.
2. Entries are sorted by recency for easy navigation.

### Updating Diary Entries

1. Navigate to the "Diary Entries" section.
2. Click on the entry you want to update.
3. Edit the text as needed and click the "Update" button.

### Deleting Diary Entries

1. In the "Diary Entries" section, find the entry you want to delete.
2. Click the "Delete" button to remove the entry permanently.

### Searching for Entries

1. Use the search functionality in the "Diary Entries" section.

## Technical Details

### Dependencies

- The frontend is built using HTML and CSS.
- Asynchronous requests are made using JavaScript.

### Project Structure

- The project follows a simple structure with HTML files for different views (create, list, details).
- CSS files are organized for styling purposes.
- JavaScript is used for handling user interactions and making API requests to the backend.

Enjoy using the Diary App frontend! If you have any questions or feedback, please don't hesitate to reach out.

# Diary App Backend

Welcome to the Diary App backend repository! This part of the application handles server-side operations, providing APIs for managing diary entries. Below, you'll find information on how to set up and use the backend.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [API Endpoints](#api-endpoints)
- [Technical Details](#technical-details)
  - [Dependencies](#dependencies)
  - [Project Structure](#project-structure)
  - [Database](#database)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository: `git clone <backend-repository-url>`
2. Navigate to the backend directory: `cd diary-app/backend`
3. Config you app in .env using Elephant SQl. 
4. Set up your database: `npm run setup-db`
3. Install dependencies: `npm install`

## Usage

### API Endpoints

- The backend exposes the following API endpoints for diary entry operations:
  - `POST /diary`: Create a new diary entry.
  - `GET /diary`: Get a list of all diary entries.
  - `GET /diary/:id`: Get details of a specific diary entry.
  - `GET /diary/:username`: Get details of a specific diary entry of a user.
  - `PATCH /diary/:id`: Update the text of a diary entry.
  - `DELETE /diary/:id`: Delete a diary entry.

## Technical Details

### Dependencies

- Built with [Express](https://expressjs.com/) and JavaScript.


### Project Structure

- The project follows a modular structure with separate files for routes, controllers, and database configuration.
- API routes are defined in `routers/diary.js`.
- Database configuration is in databse folder.
- Controllers in the `controllers` directory handle business logic.

### Database

- Utilizes an SQL database for storing diary entries.
- Configuration can be found in `.env`.
- Database schema is defined in `migrations` and `seeds` directories.

Feel free to explore and modify the backend as needed. If you have any questions or feedback, please don't hesitate to reach out.
# Diary-app
