# ChatRoulette Clone

A simple Omegle clone with just the chat feature. Connect with random strangers based on shared interests.

## Features

- Connect with random strangers
- Match based on shared interests
- Real-time chat with markdown-like formatting (bold, italic, underline)
- Typing indicators
- Responsive design

## How to Run Locally

1. Clone this repository
2. Navigate to the `server` directory
3. Install dependencies: `npm install`
4. Start the server: `npm start`
5. Open `http://localhost:3000` in your browser

## Deployment to GitHub Pages

Since this requires a backend server, GitHub Pages won't work directly. You can:

1. Deploy the backend to a service like Render, Heroku, or Railway
2. Update the socket connection URL in `public/script.js`
3. Host the frontend on GitHub Pages pointing to your backend URL

Alternatively, you can use GitHub Pages with a serverless solution like Firebase or Supabase.

## License

MIT
