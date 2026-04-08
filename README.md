# Alma Counseling Chatbot

## Introduction

Alma is an intelligent counseling chatbot built with Python and Flask. It provides emotional support, psychological assistance, and informational guidance through natural language conversations.

## Directory Structure

```
├── app/                # Core application
│   ├── __init__.py     # Flask app initialization
│   ├── config.py       # Project configuration
│   ├── models.py       # Data models
│   ├── routes.py       # Routes & business logic
│   ├── utils.py        # Utility functions
│   ├── static/         # Static resources (CSS, JS, images)
│   └── templates/      # HTML templates
├── data/               # Data files
├── requirements.txt    # Python dependencies
├── run.py              # Application entry point
└── structure.txt       # Project structure description
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/DiyiZhu/Alma-Counseling-Chatbot.git
cd Alma-Counseling-Chatbot
```

### 2. Create a virtual environment and install dependencies

```bash
python -m venv venv
source venv/bin/activate

pip install -r requirements.txt
```

### 3. Run the application

```bash
python run.py
```

The application will be available at `http://127.0.0.1:5000`.

## Features

- **Intelligent Conversation** — NLP-powered natural language interactions
- **Emotion Recognition** — Detects emotional tone from user input
- **Extensibility** — Easy to add custom modules and APIs
- **Web Interface** — Clean, responsive frontend built with Flask templates
