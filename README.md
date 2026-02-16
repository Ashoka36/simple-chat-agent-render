# Simple Chat Agent for Render

This is a simple chatbot agent that can be hosted on Render.

## How to deploy on Render

1. Create a new "Web Service" on Render.
2. Connect this GitHub repository.
3. Select "Python" as the runtime.
4. Set the Build Command: `pip install -r requirements.txt`
5. Set the Start Command: `gunicorn app:app`
6. Click "Create Web Service".

Once deployed, you can access your agent at the URL provided by Render.
