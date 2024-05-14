
# Study Notion

Study Notion is a web application for organizing and managing study materials, video lectures.

## Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/study-notion.git
   ```

2. Navigate to the project directory:
   ```bash
   cd study-notion
   ```

3. Install the server dependencies:
   ```bash
   cd server
   npm install
   ```

4. Install the client dependencies:
   ```bash
   cd ..
   cd client
   npm install
   ```

5. Create a `.env` file in the `server` directory and add your MongoDB URI:
   ```plaintext
   MONGODB_URI=your_mongodb_uri_here
   ```

6. Start the server:
   ```bash
   cd ..
   npm run dev
   ```

7. Open your browser and visit `http://localhost:3000` to view the application.

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js

## Features

- User authentication
- CRUD operations for  study materials, video lectures
- Responsive design for mobile and desktop

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



Feel free to customize the README to fit your project's specific details and requirements!
