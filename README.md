# 📝 Flask Notes Web App

A simple Flask web application that allows users to register, log in, and manage their personal notes securely.

---

## 🚀 Features

- 🔐 User Authentication
  - Sign Up
  - Log In / Log Out
- 🗒️ Notes Management
  - Add personal notes
  - View saved notes
- 🧾 Session-based user access

---

## 📁 Folder Structure

```
.
├── website/
│   ├── static/
│   │   └── index.js               # JavaScript for client-side interactions
│   ├── templates/
│   │   ├── base.html              # Base layout template
│   │   ├── home.html              # Home page for logged-in users
│   │   ├── login.html             # Login page
│   │   └── sign_up.html           # Sign up page
│   ├── __init__.py                # App factory function
│   ├── auth.py                    # Authentication routes and logic
│   ├── models.py                  # Database models
│   └── views.py                   # Main app routes (home, notes)
├── .gitignore                     # Files and folders to ignore in git
├── main.py                        # Entry point to run the app
├── requirements.txt              # Python dependencies
└── README.md                      # Project documentation
```

---

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Srinidhi2274/Flask-Notes-Web-App.git
   cd flask-notes-app
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set environment variables (for development)**
   ```bash
   export FLASK_APP=main.py
   export FLASK_ENV=development
   ```

5. **Run the app**
   ```bash
   flask run
   ```

6. **Visit the app**
   Open your browser and go to `http://127.0.0.1:5000`

---

## 🧰 Tech Stack

- Python 3
- Flask
- Jinja2 (templating)
- SQLite (via SQLAlchemy)
- HTML/CSS/JavaScript

---

## 📄 License

This project is licensed under the MIT License. Feel free to use and modify as needed.
