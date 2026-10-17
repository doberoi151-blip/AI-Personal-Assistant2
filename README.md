AI Personal Assistant
A beginner-friendly AI web application built while learning Flask. It provides two features through a simple web interface:
- Ask Anything — submit a question and display an AI-generated response.
- Summarize Email — paste an email and request a short summary.
The project uses Flask for the backend, HTML/CSS/JavaScript for the interface, and the OpenAI Python SDK to request AI responses.
Project status: Learning project / work in progress. The uploaded app.py currently needs the small fixes listed under Important code fixes before running. This README does not claim the current code runs successfully without those fixes.

Features
- Simple web interface with two forms.
- Sends form data to Flask using POST requests.
- Uses JavaScript fetch() to submit forms without reloading the page.
- Displays a loading message while a request is being processed.
- Uses an AI model to answer questions and summarize email text.
- Loads the API key from an environment variable instead of hard-coding it in Python.
Tech Stack
- Python
- Flask
- HTML
- CSS
- JavaScript (fetch() and FormData)
- OpenAI Python SDK
- python-dotenv
