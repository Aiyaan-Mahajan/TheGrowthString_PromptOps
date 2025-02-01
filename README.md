# TheGrowthString_PromptOps

## Overview

The GrowthString Project is an end-to-end application development and deployment solution that leverages modern DevOps practices and generative AI tools. This project demonstrates how to take an idea from conception to deployment using a combination of technologies, including Python, Flask, Docker, AWS, Jenkins, and Kubernetes.

## Project Structure

- **Idea Generation**: The project begins with an idea for a simple arithmetic web application that performs basic calculations (addition, subtraction, multiplication).
- **Development**: The application is developed using Python and Flask, with a simple front-end interface created using HTML, CSS, and JavaScript.
- **Version Control**: The code is managed using Git and hosted on GitHub.
- **Continuous Integration/Continuous Deployment (CI/CD)**: 
  - **AWS CodeBuild**: Used to build Docker images from the application code.
  - **Jenkins**: Automates the CI/CD pipeline, triggering builds on code changes and deploying the application.
- **Containerization**: The application is containerized using Docker, allowing for easy deployment and scalability.
- **Orchestration**: The application is deployed on a Kubernetes cluster managed by AWS EKS, ensuring high availability and scalability.

## Technologies Used

- **Programming Language**: Python
- **Web Framework**: Flask
- **Containerization**: Docker
- **Cloud Provider**: AWS (Amazon Web Services)
- **CI/CD Tools**: Jenkins, AWS CodeBuild
- **Orchestration**: Kubernetes (EKS)
- **Version Control**: Git, GitHub

## Features

- **User -Friendly Interface**: A simple web interface for performing arithmetic calculations.
- **Automated Deployment**: The application is automatically built and deployed using Jenkins and AWS CodeBuild.
- **Scalability**: The application can scale horizontally using Kubernetes.
- **Security**: Sensitive information, such as Docker Hub credentials, is securely managed using AWS SSM Parameter Store.

## Getting Started

To get started with the GrowthString Project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/growthstring.git
   cd growthstring
2. **Set Up Your Environment**:

Ensure you have Python and Flask installed.
Install Docker and configure it on your machine.
Set up AWS CLI and configure your credentials.

3.**Build and Run the Application**:

    Build the Docker image:
    docker build -t growthstring .
    
    Run the Docker container:
    docker run -p 5000:5000 growthstring
    
4.**Access the Application**:
Open your web browser and navigate to http://localhost:5000.


