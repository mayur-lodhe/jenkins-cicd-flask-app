# Jenkins CI/CD Flask App on AWS EC2

This project demonstrates a simple CI/CD pipeline using Jenkins, Docker, and AWS EC2.

## Steps
1. Launch an EC2 instance (Ubuntu).
2. Install Jenkins and Docker.
3. Clone this repo into Jenkins.
4. Run the pipeline → Jenkins will build, test, and deploy the Flask app.
5. Access the app at `http://<EC2-Public-IP>:5000`.

## Files
- `app.py` → Flask app
- `requirements.txt` → Dependencies
- `Dockerfile` → Container setup
- `Jenkinsfile` → CI/CD pipeline
