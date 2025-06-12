# JARVIS Chatbot (Django Project)

A simple web-based chatbot built with Django and Bootstrap, featuring a dark theme and persistent search history. This was my 2nd Year Mini Project i came across recently so I thought to share this in Github.

## Features
- **Chatbot Interface:** Ask questions and get answers from JARVIS.
- **Search History:** Sidebar shows all previous queries (stored in your browser).
- **Responsive Design:** Works well on desktop and mobile.

## Getting Started
1. **Clone the repository:**
   ```
   git clone https://github.com/Abhay-Kushwaha/ChatBot-II-year
   cd ChatBot-II-year
   ```
2. **Create and activate a virtual environment:**
   ```
   python -m venv venv
   venv\Scripts\activate   # On Windows
   # or
   source venv/bin/activate  # On Linux/macOS
   ```
3. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```
4. **Start the server:**
   ```
   python manage.py runserver
   ```
6. **Open in your browser:**
   ```
   http://127.0.0.1:8000/
   ```

## Notes
- Previous searches are stored in your browser's localStorage.
- The chatbot logic can be extended in Django views.
- UI uses Bootstrap 4 for styling.