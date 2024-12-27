```
jericho@Home-iMac Go % docker init

Welcome to the Docker Init CLI!

This utility will walk you through creating the following files with sensible defaults for your project:
  - .dockerignore
  - Dockerfile
  - compose.yaml
  - README.Docker.md

Let's get started!

? What application platform does your project use? Go
? What version of Go do you want to use? 1.23.4
? What's the relative directory (with a leading .) of your main package? .
? What port does your server listen on? 8000

✔ Created → .dockerignore
✔ Created → Dockerfile
✔ Created → compose.yaml
✔ Created → README.Docker.md

→ Your Docker files are ready!
  Review your Docker files and tailor them to your application.
  Consult README.Docker.md for information about using the generated files.

! Warning → No go.mod file was found but is required to build your application. Create it with: go mod init your-package-name.

What's next?
  Start your application by running → docker compose up --build
  Your application will be available at http://localhost:8000
```
