# Flask App Docker Setup

This project uses Python 3.12 and Flask.

## How to build and run

1. **Build the Docker image:**
   ```
   docker build -t flask-app .
   ```

2. **Run the Docker container:**
   ```
   docker run -p 5000:5000 flask-app
   ```

3. **Access the app:**
   Open [http://localhost:5000](http://localhost:5000) in your browser.

## Files

- `flask_1.py` — Main Flask application
- `requirements.txt` — Python dependencies (add `flask`)
- `Dockerfile` — Instructions to build the Docker