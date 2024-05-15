# Microservice for Database Interaction

This microservice serves as an intermediary between the frontend and the database, handling incoming data from the frontend and storing it in a MongoDB database.

## Routes

- **POST /save-text**: Receives input from the frontend, saves it to the database, and updates existing conversations if an ID is provided.
  - **Request Body**: `{ _id: String, content: String }`
  - **Response**: `{ message: String, _id: String }`


## Technologies Used

- **ExpressJS**: Web application framework for Node.js.
- **mongoose**: Elegant MongoDB object modeling for Node.js.

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- MongoDB instance

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/microservice-database.git
   cd microservice-database
   ```

2. Install dependencies:

    ```bash
    npm install
    ```
