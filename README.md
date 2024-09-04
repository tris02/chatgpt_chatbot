# ChatGPT Chatbot

This is a simple chatbot project using OpenAI's GPT-3.5-Turbo model. The chatbot interacts with users via a web interface. Built with Node.js and Express.js.

## Features
- Real-time chatbot interactions
- Uses OpenAI's GPT-3.5-Turbo API
- Responsive and simple UI

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (v12 or higher)
- OpenAI API Key

## File structure

```bash
chatgpt_chatbot/
│
├── .env                 # Stores your OpenAI API key
├── config.js            # Configuration file to load the API key from the .env file
├── package.json         # Project metadata and dependencies
├── server.js            # Express.js server that handles routing and API calls
├── public/
│   ├── chat.png         # Chat logo for the UI
│   ├── index.html       # Frontend interface for the chat
│   ├── style.css        # Styling for the chat UI
│   └── main.js          # Handles frontend interactions and fetching chatbot responses
├── openai.js            # Handles communication with the OpenAI API
└── README.md            # Instructions for setup and usage 

### Steps
1. Clone the repository:

   ```bash
   git clone https://github.com/tris02/chatgpt_chatbot.git

2. Navigate to the project directory 

   ```bash
   cd chatgpt_chatbot

4. Install the dependencies.
   This will install Express.js and OpenAI client. 

   ```bash
   npm install

6. Set Up Environment Variables.
   You will need to edit the .env file in the root of the project to store your OpenAI API key.

8. Start the Server.
   Once everything is set up, you can start the server.
   The server will start on port 3000. Open your browser and go to: http://localhost:3000.

   ```bash
   node server.js

9. Interacting with the Chatbot.
   The UI allows you to interact with the chatbot. You can type messages, and the chatbot will respond with replies generated by the OpenAI GPT-3.5-Turbo model.
