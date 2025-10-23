🧠 Gradio Chat Interface for Ollama Phi Model

This is a practice project that demonstrates how to build a simple chat interface using Gradio and the Ollama Phi model running locally.

It allows users to send messages and get AI-generated responses in a clean, interactive web interface.

🚀 Features

🗣️ Chat interactively with a local Phi model

🧹 Clear the chat with one click

🌐 Launches in a browser automatically

🧩 Built with Gradio and OpenAI’s Python client

🛠️ Requirements

Make sure you have the following installed:

Python 3.8+

Ollama
 (running locally)

Gradio

OpenAI Python package

You can install the required packages by running:

pip install gradio openai

▶️ How to Run

Save the Python file (e.g., gradio_chat.py).

Make sure Ollama is running locally (ollama serve).

Run the script:

python gradio_chat.py


Wait for the Gradio interface to open in your browser.

💬 Example Use

You can start chatting immediately once the interface opens:

User: Hello!
AI: Hi there! How can I help you today?

🧰 Notes

This is a practice project for learning how to connect Gradio with local models.

The API key "nokeyneeded" is just a placeholder for local testing.

Model used: "phi:latest" — can be changed to any model supported by your Ollama installation.