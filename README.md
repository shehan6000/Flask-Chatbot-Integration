# Flask Chatbot Integration

This project demonstrates how to set up a back-end server using Flask and integrate a simple chatbot model into a web application. The chatbot is based on the `facebook/blenderbot-400M-distill` model from the Hugging Face library. The application includes a front-end webpage that communicates with the back-end server to handle user interactions with the chatbot.

## Learning Objectives

- Set up a back-end server using Flask.
- Integrate a chatbot into the Flask server.
- Create a front-end webpage to communicate with the back-end server.

## Prerequisites

Before you begin, make sure you have completed the initial lab on building a simple terminal chatbot. This project builds on that foundation.

## File Descriptions

- `app.py`: The main Flask application file containing the back-end server setup and chatbot integration.
- `requirements.txt`: Lists the Python dependencies required to run the application.
- `static/script.js`: Contains JavaScript code for the front-end to handle user interactions and communicate with the back-end server.
- `templates/index.html`: The main HTML file for the front-end webpage.
- `README.md`: Project documentation file.

## Installation and Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Flask-Chatbot-Integration.git
    cd Flask-Chatbot-Integration
    ```

2. Install dependencies:
    ```sh
    python3.11 -m pip install -r requirements.txt
    ```

3. Run the Flask application:
    ```sh
    flask run
    ```

4. Access the application:
    - Open a web browser and navigate to `http://127.0.0.1:5000/` to view the chatbot interface.

## Back-End Server (Flask) Setup

1. Install Flask and CORS:
    ```sh
    python3.11 -m pip install flask
    python3.11 -m pip install flask_cors
    ```

2. Create `app.py` as described above.

## Front-End Setup

1. Clone the template repository:
    ```sh
    git clone https://github.com/ibm-developer-skills-network/LLM_application_chatbot.git
    ```

2. Move `app.py` into the `LLM_application_chatbot` directory:
    ```sh
    mv app.py LLM_application_chatbot/
    ```

3. Modify `index.html` and `script.js` to point to your Flask server:
    - Update the URL in `
