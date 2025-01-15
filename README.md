# Task Management Application

This is a simple task management application built with Python Flask for the backend and React for the frontend.

## Features

- Add, view, and manage tasks
- Store tasks in a SQLite database
- RESTful API with Flask
- Responsive UI with React

## Prerequisites

- Python 3.x
- Node.js and npm

## Getting Started

### Backend Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/task-manager.git
   cd task-manager

2. **Create a virtual environment**:
   ```bash
    python -m venv venv
    source venv/bin/activate
    # On Windows use `venv\Scripts\activate`

2. **Install dependencies**:
    ```bash
    pip install Flask SQLAlchemy Marshmallow
    
3. **Run the Flask app**:
    ```bash
    python app.py

Frontend Setup
Navigate to the frontend directory:

cd frontend
Install dependencies:

npm install
Start the React app:

npm start
API Endpoints
GET /tasks: Retrieve all tasks
POST /task: Add a new task

Project Structure
task-manager/
├── app.py
├── models.py
├── requirements.txt
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   └── TaskList.js
│   │   ├── App.js
│   │   └── index.js
│   ├── public/
│   ├── package.json
│   └── ...
└── ...
Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgements
Flask
React
Create React App
