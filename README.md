# Chat App

## Overview
This is a real-time chat application that allows users to communicate seamlessly. The project is built using modern web technologies and follows best practices for scalability and performance.

## Features
- Real-time messaging
- User authentication
- Private and group chats
- Message notifications
- Typing indicators
- Responsive UI design

## Technologies Used
- Frontend: React.js / Next.js
- Backend: Node.js / Express
- Database: MongoDB / Cloudinary
- WebSockets: Socket.io
- Authentication: JWT

## Installation

### Prerequisites
Ensure you have the following installed on your system:
- Node.js (v16+)
- npm or yarn

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/assifhamilton/chat_app.git
   ```
2. Navigate to the project folder:
   ```sh
   cd chat_app
   ```

   ```sh
   cd backend
   ```

3. Install dependencies:
   ```sh
   npm install
   ```

   The same should be repeated from Project folder

   ```sh
   cd frontend
   ```

   ```sh
   npm install
   ```
   
5. Configure environment variables:
   - Create a `.env` file in the root directory
   - Add the required API keys and database credentials
   
   ```sh
   MONGODB_URI=...
   PORT=5001
   JWT_SECRET=...

   CLOUDINARY_CLOUD_NAME=...
   CLOUDINARY_API_KEY=...
   CLOUDINARY_API_SECRET=...

   NODE_ENV=development
   ```
   
6. Start the development server:
   Backend:
   ```sh
   cd backend
   ```

   ```sh
   npm run dev
   ```

   Frontend:
   ```sh
   cd frontend
   ```

   ```sh
   npm run dev
   ```

## Usage
- Open the browser and go to `http://localhost:5173`
- Register a new account or log in
- Start a chat with other users

## Deployment
To deploy the application, you can use:
- Vercel for frontend
- Render for backend



## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Push to the branch and create a Pull Request

