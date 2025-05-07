# mlops 


Create a Flask app that returns “Hello, World!”, containerize it with Docker, and run it.

 Requirements
•	Python 3.x installed
•	Docker installed
•	Any OS (Linux, MacOS, Windows)
•	A code editor (e.g., VS Code)

📁 Project Structure
hello-docker-flask/
│
├── app.py
├── requirements.txt
└── Dockerfile


Step 1: Create a Project Folder
Open terminal or command prompt and run:

mkdir hello-docker-flask
cd hello-docker-flask

Step 2: Create the Flask App (app.py)
Create a file named app.py and add:



Step 3: Create requirements.txt

# This file tells Docker what dependencies to install.
flask


Step 4: Create the Dockerfile


Step 5: Build the Docker Image
In the terminal, inside the hello-docker-flask folder:
docker build -t hello-flask .

Step 6: Run the Container
docker run -d -p 5000:5000 hello-flask

✅ Test the App
Open your browser and go to:
http://localhost:5000

Hello, World!

