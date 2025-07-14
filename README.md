# AI Code Review Application

This project is a full-stack web application that provides automated code review functionality using AI. It consists of a backend API service built with Node.js and Express, and a frontend React application that allows users to input code and receive AI-generated reviews.

## Technologies Used

### Backend
- Node.js
- Express.js
- @google/generative-ai
- CORS
- dotenv

### Frontend
- React 19
- Vite
- Axios
- PrismJS, Highlight.js, rehype-highlight for syntax highlighting
- react-simple-code-editor for code editing
- react-markdown for rendering markdown

## Setup Instructions

### Backend

1. Navigate to the `BackEnd` directory:
   ```bash
   cd BackEnd
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the `BackEnd` directory and add any necessary environment variables (if applicable).

4. Start the backend server:
   ```bash
   node server.js
   ```

   The backend server will run on [http://localhost:3000](http://localhost:3000).

### Frontend

1. Navigate to the `Frontend` directory:
   ```bash
   cd Frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and go to the URL provided by Vite (usually [http://localhost:5173](http://localhost:5173)).

## Usage

- In the frontend application, you can write or paste JavaScript code into the code editor.
- Click the **Review** button to send the code to the backend AI service for review.
- The AI-generated review will be displayed on the right side of the screen in markdown format with syntax highlighting.

## API Endpoint

- `POST /ai/get-review` - Accepts a JSON payload with a `code` field containing the code to review. Returns the AI-generated review as a response.

## License

This project is licensed under the ISC License.

## Author

[Your Name Here]
