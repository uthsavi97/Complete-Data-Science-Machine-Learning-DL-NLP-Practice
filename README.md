# Complete-Data-Science-Machine-Learning-DL-NLP-Practice

# [Flask Introduction](#flask-introduction)

Flask is a lightweight and flexible web framework for Python that makes it easy to build web applications quickly. It’s simple to get started with and provides the essential tools to create web apps, APIs, and more.

## Key Features
- **Minimal and Simple:** Focuses on simplicity with minimal boilerplate.
- **Flexible:** Add only the components you need.
- **Built-in Development Server:** Test your app locally.
- **Routing:** Map URLs to Python functions easily.
- **Jinja2 Templating:** Render dynamic HTML.
- **Extension Support:** Integrate features like authentication and database access.

## Getting Started

### 1. Install Flask
Make sure you have Python installed, then run:
```bash
pip install Flask
```

### 2. Create a Simple App
Create a file called `app.py` and add the following code:
```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, Flask!"

if __name__ == "__main__":
    app.run(debug=True)
```

### 3. Run the App
In your terminal, run:
```bash
python app.py
```
You should see output indicating the app is running.

### 4. Access Your App
Open your browser and go to:
```
http://127.0.0.1:5000/
```
You should see "Hello, Flask!" displayed.

## Why Use Flask?
- Ideal for small to medium projects.
- Provides control without unnecessary complexity.
- Great for prototyping and learning web development with Python.

## Next Steps
- Explore routing, templates, and forms.
- Integrate with databases.
- Deploy your app to the cloud.



