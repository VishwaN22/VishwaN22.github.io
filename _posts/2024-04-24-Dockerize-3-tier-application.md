Introduction:
In this tutorial, we will dockerize a three-tier application consisting of a backend server, MongoDB database, and frontend interface. Docker allows us to package each component of our application into a container, providing consistency and portability across different environments.

Prerequisites:

Docker installed on your system

![Docker Image](/images/docker1.jpg)


Step 1: Dockerizing the Backend:

Create a Dockerfile for your backend application. Here's an example Dockerfile for a Node.js backend:
![Docker Image](/images/docker3.jpg)

![Docker Image](/images/docker5.jpg)


![Docker Image](/images/docker7.jpg)

![Docker Image](/images/docker10.jpg)



![Docker Image](/images/docker14.jpg)

Step 2: Dockerizing MongoDB:

![Docker Image](/images/docker11.jpg)

![Docker Image](/images/docker12.jpg)




Pull the MongoDB official Docker image:

reate a Dockerfile for MongoDB if you need to customize the configuration.
![Docker Image](/images/docker13.jpg)
Step 3: Dockerizing the Frontend:

Create a Dockerfile for your frontend application. Here's an example Dockerfile for a React frontend:
![Docker Image](/images/docker15.jpg)

![Docker Image](/images/docker16.jpg)

Build the Docker image for the frontend:

![Docker Image](/images/docker17.jpg)

![Docker Image](/images/docker18.jpg)

Create a docker-compose.yml file in your project directory:

![Docker Image](/images/docker19.jpg)

![Docker Image](/images/docker20.jpg)

![Docker Image](/images/docker21.jpg)

Step 5: Starting the Application:

Navigate to your project directory containing the docker-compose.yml file.
Start the application using Docker Compose:

This command will start all three containers (backend, MongoDB, frontend) and link them together as specified in the docker-compose.yml file.

Pushing to DockerHub:
Login to Docker and execute the following to push image

![Docker Image](/images/docker24.jpg)

![Docker Image](/images/docker25.jpg)

![Docker Image](/images/docker27.jpg)

Conclusion:
In this tutorial, we learned how to dockerize a three-tier application using Docker and Docker Compose. By containerizing each component of our application, we ensure consistency and ease of deployment across different environments. Docker simplifies the development and deployment process, making it a valuable tool for modern software development.