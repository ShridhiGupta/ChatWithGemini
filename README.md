# ChatWithGemini

An interactive terminal-based chatbot powered by Google Gemini AI and built with Node.js.

This project allows users to chat directly with Google's Gemini model from the command line while maintaining conversation history for contextual responses.

![Node.js](https://img.shields.io/badge/Node.js-18+-green.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange.svg)

---

## Overview

ChatWithGemini is a lightweight command-line chatbot that enables seamless interaction with Google's Gemini AI models. It is designed for developers who want a simple and efficient way to access AI capabilities directly from the terminal.

---

## Features

* Interactive chat interface in the terminal
* Powered by Google Gemini AI
* Maintains conversation history for contextual responses
* Lightweight and easy to set up
* Built with Node.js
* Simple and developer-friendly codebase

---

## Demo

```text
You: Hello Gemini!

Gemini: Hey there! How can I help you today?
```

---

## Project Structure

```text
ChatWithGemini
├── index.js
├── package.json
├── .env
└── README.md
```

---

## Getting Started

### Prerequisites

Ensure you have the following installed:

* Node.js v18 or later
* npm
* A Google Gemini API key

### Clone the Repository

```bash
git clone https://github.com/ShridhiGupta/ChatWithGemini.git
cd ChatWithGemini
```

### Install Dependencies

```bash
npm install
```

### Configure the API Key

Create a `.env` file in the project root directory and add:

```env
API_KEY=your_gemini_api_key_here
```

Replace `your_gemini_api_key_here` with your actual Gemini API key.

### Run the Application

```bash
node index.js
```

---

## Tech Stack

* Node.js
* Google Gemini API (`@google/genai`)
* readline-sync
* dotenv

---

## How It Works

1. The user enters a prompt in the terminal.
2. The prompt is sent to the Gemini API.
3. Gemini generates a response.
4. The response is displayed in the terminal.
5. The conversation history is preserved to provide context-aware responses.

---

## Contributing

Contributions are welcome.

To contribute:

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/your-feature-name
```

3. Commit your changes.

```bash
git commit -m "Add your feature"
```

4. Push to your branch.

```bash
git push origin feature/your-feature-name
```

5. Open a Pull Request.

For major changes, please open an issue first to discuss your proposed improvements.

---

## Future Improvements

* Streaming responses
* Chat history persistence
* Voice input and output
* Support for multiple Gemini models
* Custom system prompts
* Enhanced terminal UI

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

## Support

If you find this project useful:

* Star the repository
* Share it with others
* Contribute to improve it

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Built using Node.js and Google Gemini AI.
