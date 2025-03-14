# Personal Portfolio Website

A modern, responsive personal portfolio website built with Go and HTMX.

## Tech Stack

- [Go](https://go.dev/) - Backend server
- [Echo](https://echo.labstack.com/) - Web framework
- [Templ](https://templ.guide/) - HTML templating
- [TailwindCSS](https://tailwindcss.com/) - Styling
- [Air](https://github.com/cosmtrek/air) - Live reloading
- [Task](https://taskfile.dev/) - Task runner
- [Docker](https://www.docker.com/) - Containerization

## Development

Start the development server with hot-reload:

```sh
task dev
```

Build the project:
Build Docker container:

## Project Structure

## Deployment

Automated deployment via GitHub Actions:

- Builds Docker image on push to master
- Pushes to Docker Hub
- Deploys to VPS via SSH

## Docker

Built with a multi-stage build:

- Go builder stage compiles binary
- Final stage uses distroless base image
- Exposes port 8080

## License

This project is open source and available under the MIT license.
