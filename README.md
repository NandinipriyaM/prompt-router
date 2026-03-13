# LLM-Powered Prompt Router

This project implements a prompt router that classifies user intent and routes to specialized expert prompts.

## Setup

1. Clone the repository.
2. Create a virtual environment: `python -m venv venv`
3. Activate it: `source venv/Scripts/activate` (Git Bash) or `venv\Scripts\activate` (cmd)
4. Install dependencies: `pip install -r requirements.txt`
5. Copy `.env.example` to `.env` and add your OpenAI API key.
6. Run the test messages: `python -m app.main`

## Docker

Build and run with: