# alx-files_manager
This is a project file 
# Files Manager

A simple file management API built with Node.js, Express, MongoDB and Redis.

## Features

- User authentication via tokens
- File upload and management
- Thumbnail generation for images
- Basic CRUD operations on files
- File permissions and sharing

## Technologies Used

- Node.js
- Express
- MongoDB
- Redis
- Bull (for job queues)
- Jest (for testing)

## Installation
To install and run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/sheshbazzarr/alx-files_manager.git
   ```

2. Navigate to the project directory:
   ```bash
   cd alx-files_manager
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Set up environment variables:
   Create a `.env` file in the root directory and add the following variables:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_uri
   REDIS_HOST=your_redis_host
   REDIS_PORT=your_redis_port
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

6. Run tests:
   ```bash
   npm test
   ```

Now, you should be able to access the API at `http://localhost:5000`.

For more details, refer to the [API documentation](https://github.com/sheshbazzarr/alx-files_manager.git).







