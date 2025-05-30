# Interactive Math Tutor Chatbot

This Python-based chatbot is designed to help elementary students understand and solve math problems interactively. It acts as a virtual tutor, guiding users through basic arithmetic operations using natural language.

---

## Features

- Supports basic math problems:
  - Addition, subtraction, multiplication, division
- Responds in a conversational tone
- Explains steps clearly to support learning
- Handles multiple interactions in a session
- Modular code structure for easy updates and scaling

---

## Setup and API Key Configuration

This app uses OpenAI's API to generate responses from a fine-tuned GPT-3.5 model. To run the app, you need an OpenAI API key.

### How to get your OpenAI API key:

1. Sign up or log in at [OpenAI](https://platform.openai.com/).
2. Navigate to your account's API keys section.
3. Create a new secret key or use an existing one.

### How to set the API key for this app:

- **Locally**, create a `.env` file in your project folder with the following line:
OPENAI_API_KEY=your_api_key_here

- Or export it in your terminal session:
```bash
export OPENAI_API_KEY=your_api_key_here

The app reads this environment variable at runtime to authenticate requests to OpenAI.