
# AI Chat Bot

A simple and responsive AI chat application built with React. This project allows users to chat with an AI-powered assistant. The app features chat management (creating, deleting, switching between chats) and an emoji picker. It stores chat history locally in the browser's `localStorage`.

## Features:
- **Start Chat**: Begin a new chat session with the AI.
- **Chat History**: Store and manage previous chats in local storage.
- **Emoji Picker**: Add emojis to your messages.
- **AI Responses**: The app interacts with an AI model through API requests and generates AI responses.
- **Responsive UI**: The app works well on both desktop and mobile devices.

## Technologies Used:
- **React**: JavaScript library for building user interfaces.
- **UUID**: For generating unique chat session IDs.
- **Fetch API**: To interact with external AI models.
- **CSS**: Custom styling for responsive and aesthetic user interface.

## Prerequisites:
Ensure that you have the following installed:
- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- **npm** or **yarn**: Package managers to install dependencies.

## Installation:
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/ai-chat-bot.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ai-chat-bot
   ```

3. Install dependencies:
   ```bash
   npm install
   ```
   or, if you're using yarn:
   ```bash
   yarn install
   ```

## Setup:
1. **API Key**: Replace the placeholder `GEMINI_API_KEY` in `ChatBotApp.jsx` with your actual Gemini API key.
2. The chat history is stored in `localStorage`, and will persist across sessions.

## Running the App:
Once everything is set up, you can start the development server with:

```bash
npm start
```

or if you're using yarn:

```bash
yarn start
```

Visit `http://localhost:3000` in your browser to see the app in action.

## File Structure:
- `src/`
  - `components/`: Contains React components for the app's chat interface.
    - `ChatBotStart/`: The start screen where the user can begin a new chat.
    - `ChatBotApp/`: The main chat interface where users interact with the AI.
  - `App.jsx`: The main entry point of the application.
  - `index.css`: Global styles for the application.
  - `ChatBotApp.css`: Specific styles for the ChatBotApp component.
  - `ChatBotStart.css`: Specific styles for the ChatBotStart component.

## Contributing:
Feel free to fork the repository and submit pull requests. If you find any bugs or issues, please create an issue in the Issues tab.

## License:
MIT License. See the LICENSE file for more details.

## Acknowledgements:
- **React**: [React Documentation](https://reactjs.org/docs/getting-started.html)
- **UUID**: [UUID Documentation](https://www.npmjs.com/package/uuid)
- **Gemini API**: [Google Gemini Documentation](https://developers.google.com/generative-language)
