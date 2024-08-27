**Name:** Bhavdip Akabari  
**Company:** Codtech It Solutions  
**ID:** CT08DS6150  
**Domain:** DevOps Intern  
**Duration:** Aug To Aug 2024  
**Mentor:** Muzammil Ahmed  

## Overview of the Project

### Project: DOCKER CONTAINERIZATION

### Objective: 
Containerize a web application using Docker to ensure consistent environments
 across development, testing, and production. Write a Dockerfile to containerize a
 simple web application. Build and run Docker containers locally.
![Screenshot (22)](https://github.com/user-attachments/assets/ee7e1158-c064-4d2a-a32d-b74a371a1d5c)
output of this web app
![Screenshot (23)](https://github.com/user-attachments/assets/9734f739-6d83-4bbb-9588-2787ad523098)
Container run in docker


### Key Activities:
- **Step 1: Create a Simple and Visually Appealing Web Application**
  - 1.Install Python and Pip
  - 2.Create a New Project Directory
  - 3.Set Up a Virtual Environment
  - 4.Activate the Virtual Environment
  - 5.Install Flask
  - 6.Create the Flask Application
    ![Screenshot 2024-08-27 173437](https://github.com/user-attachments/assets/98b538b9-341a-4c3d-95d6-d5a4fe206fa8)

  - 7.Create a Template Directory and HTML File
    ![Screenshot 2024-08-27 173533](https://github.com/user-attachments/assets/a81c4151-ee2d-4c0b-ac22-f5de3d18113e)

  - 8.Create a requirements.txt File
- **step 2: Write a Dockerfile to Containerize the Application**
  - Create a Dockerfile in Your Project Directory
    ![Screenshot 2024-08-27 173454](https://github.com/user-attachments/assets/50ddd42a-7c5a-4fc5-b56b-74786f798d68)

- **step 3:  Build and Run Docker Containers Locally
  - 1.Build the Docker Image:  
      Open Command Prompt or PowerShell in the enhanced-web-app directory and run:  
      command "docker build -t userid/enhanced-flask-app ."  
      This command builds the Docker image for your enhanced Flask application and tags it as enhanced-flask-app
  - 2.Run the Docker Container:  
      Run the Docker container to ensure the app works:
      command "docker run -p 5000:5000 userid/enhanced-flask-app"
      This command runs the Docker container and maps port 5000 of the container to port 5000 on your local machine.
  - 3.Access the Running Application:  
      Open a web browser and go to http://localhost:5000 to see your enhanced Flask application in action.


### Technology Used: 
- Python
- Docker
- Html
- Bootstrap

### Summary:
By following these steps, you have created a simple yet visually appealing Flask web application, written a Dockerfile to containerize it, built a Docker image, and run the Docker container locally. This setup demonstrates how Docker can ensure consistent environments across development, testing, and production.
