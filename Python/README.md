```
jericho@Home-iMac Python % docker init

Welcome to the Docker Init CLI!

This utility will walk you through creating the following files with sensible defaults for your project:
  - .dockerignore
  - Dockerfile
  - compose.yaml
  - README.Docker.md

Let's get started!

? What application platform does your project use? Python
? What version of Python do you want to use? 3.13.1
? What is the command you use to run your app (e.g., gunicorn 'myapp.example:app' --bind=0.0.0.0:8000)? gunicorn 'myapp.example:app' --bind=0.0.0.0:8000

✔ Created → .dockerignore
✔ Created → Dockerfile
✔ Created → compose.yaml
✔ Created → README.Docker.md

→ Your Docker files are ready!
  Review your Docker files and tailor them to your application.
  Consult README.Docker.md for information about using the generated files.

! Warning → No requirements.txt file found. Create one with the dependencies for your application, including an entry for the gunicorn package, before running it.

What's next?
  Start your application by running → docker compose up --build
  Your application will be available at http://localhost:8000
```
