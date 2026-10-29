
# DevOps Assignment 2

## Student Information
- Name: Samama Ali
- Roll Number: FA23-BAI-024
- Program: BS Artificial Intelligence

## Project Description
This is a personal portfolio website developed
using HTML and CSS for DevOps Assignment 2.

The website includes an introduction, student
information, and four DevOps lab topics.

## Technologies Used
- HTML and CSS
- Git and GitHub
- Docker
- GitHub Actions
- GitHub Webhooks

## Project Features
- Personal portfolio website
- Responsive design
- DevOps Labs section
- Version control with Git
- Docker containerization
- Automated CI/CD workflow

## Run Website Locally
1. Download or clone the repository.
2. Open the project folder.
3. Open index.html in a web browser.

## Docker Instructions
Build the Docker image:

    docker build -t devops-a2 .

Run the Docker container:

    docker run -d -p 8080:80 devops-a2

Open the website:

    http://localhost:8080

## GitHub Actions
The CI/CD workflow checks the HTML page,
builds the Docker image, and publishes
the latest image to Docker Hub on main pushes.

## Author
Samama Ali
FA23-BAI-024
