# Maverick

Maverick is a lightweight, local web-based chatbot interface built with vanilla HTML, CSS, and JavaScript. It uses a Python backend (`proxy.py`) to securely proxy requests to a locally running Ollama API, enabling fast and private AI conversations powered by local LLMs such as LLaMA 3.

## Features

- Simple and responsive web-based chat UI
- Connects to locally hosted LLMs via Ollama
- Python backend using Flask for secure request handling
- Fully offline and privacy-respecting setup

## Architecture

maverick/
├── index.html 
├── style.css 
├── script.js 
├── proxy.py
└── README.md


## Requirements

- Python 3.7 or higher
- Flask
- requests
- Ollama with a local model (e.g. `llama3`)
- A modern web browser

## Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/Prabh1306/Maverick-Ai.git
   cd Maverick-Ai

##Install Python dependencies

pip install flask requests
Run a local Ollama model

## Make sure Ollama is installed and run a model like LLaMA 3:

ollama run llama3


## Start the Python backend

python proxy.py


This will start the Flask server at http://localhost:5000.



You can open index.html directly in your browser or run a simple local HTTP server:

Then navigate to http://localhost:5000 to start chatting.
