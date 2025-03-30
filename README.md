# AI Recommendation System

A Flask-based web application that provides disease predictions and recommendations based on symptoms.

## Features

- Disease prediction based on symptoms
- Detailed disease descriptions
- Precautions and recommendations
- Modern, responsive UI

## Deployment Instructions

### Using Python Anywhere

1. Create a Python Anywhere account at https://www.pythonanywhere.com/

2. Upload your files:
   - Upload all files from this repository to your Python Anywhere account
   - Make sure to maintain the same directory structure

3. Set up a new web app:
   - Go to the "Web" tab
   - Click "Add a new web app"
   - Choose "Flask" as the framework
   - Select Python 3.10 or later
   - Set the working directory to your project folder
   - Set the WSGI configuration file to point to your main.py

4. Configure the web app:
   - Set the source code directory to your project folder
   - Set the working directory to your project folder
   - Set the WSGI configuration file to point to your main.py
   - Set the application startup file to main.py
   - Set the application callable to app

5. Install dependencies:
   - Open a Bash console
   - Navigate to your project directory
   - Run: `pip install -r requirements.txt`

6. Reload your web app:
   - Go back to the "Web" tab
   - Click the "Reload" button

Your application should now be live at your Python Anywhere URL!

## Local Development

1. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python main.py
   ```

4. Open your browser and navigate to `http://localhost:5000` 