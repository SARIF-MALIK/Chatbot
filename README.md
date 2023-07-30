# AI Chatbot with ChatGPT

This is a simple AI chatbot built using the OpenAI GPT-3 API, Node.js and Express. It uses the `openai` npm package to interact with the GPT-3 API and provides a web interface for users to chat with the bot.

## Features

- Chat with the AI chatbot in natural language
- Get intelligent responses based on the context of the conversation
- Customize the behavior of the chatbot by adjusting various parameters

## Installation

To use the AI chatbot, you will need to have Node.js and npm installed on your machine. Once you have installed these, you can clone the repository and install the dependencies by running the following commands:

``` Bash
git clone https://github.com/uixaadi/aichatbot-chatgpt.git
cd aichatbot-chatgpt
npm install
```

## Usage

To use the AI chatbot, you will need to set up the OpenAI API key. You can get your API key by signing up for an account on the OpenAI website and following the instructions to generate an API key.

Once you have your API key, create a new file called `.env` in the root directory of the project and add the following line:

```javascript
OPENAI_API_KEY=<your API key>
```


Replace `<your API key>` with your actual API key.

To start the server, run the following command:

```bash
npm start
```


This will start the server on `http://localhost:3000/`, where you can interact with the AI chatbot.

## Contributing

If you find any issues with the AI chatbot or have any suggestions for improvement, please feel free to contribute to the project. You can submit a pull request or open an issue on the GitHub repository.

### Author

[@uixaadi](https://github.com/uixaadi)
