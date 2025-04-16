# Rasa Chatbot

This project is a Rasa-based chatbot. Follow the steps below to set up and start the bot.

## Prerequisites

1. Install Python (version 3.7 or higher).
2. Install `pip` (Python package manager).
3. Install `virtualenv` (optional but recommended).

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>

2. **Create a Virtual Environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate
   
3. **Install Rasa**:
   ```bash
   pip install rasa

4. **Train the model**:
   ```bash
   rasa train

# Starting the Chatbot

To start the chatbot in interactive mode, run the following command:

````bash
rasa shell
