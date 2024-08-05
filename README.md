# Langchain Streaming

## Project Overview

This project is a FastAPI-based application that generates humorous responses related to a given input using LangChain and OpenAI's GPT-4. The application serves a simple web interface where users can input a topic and receive a streaming response with a clever and humorous answer.

## Features

- **FastAPI**: Provides the backend framework for handling HTTP requests and responses.
- **LangChain**: Utilizes the LangChain library to create a prompt template and process the input through the OpenAI model.
- **Streaming Responses**: Streams the generated response to the client in real-time.
- **Static Files**: Serves static HTML, CSS, and JavaScript files for the web interface.
- **CORS**: Configured to allow cross-origin resource sharing.

## Files

### 1. `main.py`

This is the main application file that sets up the FastAPI app, handles requests, and integrates with the LangChain model.

### 2. `index.html`

The HTML file provides the structure of the web interface where users can input their topics and view the generated humorous responses.

### 3. `style.css`

This CSS file styles the web interface, ensuring it is visually appealing and user-friendly.

### 4. `script.js`

The JavaScript file handles the frontend logic, including capturing user input, making requests to the backend, and displaying the streaming responses.

## Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Haziq046/langchain-streaming.git
    cd langchain-streaming
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables**:
    Create a `.env` file in the root directory and add your OpenAI API key:
    ```
    OPENAI_API_KEY=your-openai-api-key
    ```

4. **Run the application**:
    ```bash
    uvicorn main:app --reload
    ```

5. **Open your browser**:
    Go to `http://127.0.0.1:8000` to access the web interface.


