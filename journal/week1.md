# Week 1 — App Containerization

## Required Homework
- ### Containerizing the Application
I was able to containerize the application with Docker, and it ran successfully.

![Image](images/containerizedApp.jpg)
[Frontend Dockerfile](https://github.com/Chxnedu/aws-bootcamp-cruddur-2023/blob/main/frontend-react-js/Dockerfile)
[Backend Dockerfile](https://github.com/Chxnedu/aws-bootcamp-cruddur-2023/blob/main/backend-flask/Dockerfile)
[Docker Compose File](https://github.com/Chxnedu/aws-bootcamp-cruddur-2023/blob/main/docker-compose.yml)

- ### Documenting Notification Endpoint
I added the notification endpoint to my [OpenAPI File](https://github.com/Chxnedu/aws-bootcamp-cruddur-2023/blob/main/backend-flask/openapi-3.0.yml)

- ### Flask Backend Endpoint for Notifications
I wrote a flask backend endpoint for Notifications and confirmed that it worked

![Image](images/backendAPIendpoint.jpg)

- ### React page for Notifications
I wrote a react page for notifications

![Image](images/reactNotificationsPage.jpg)

- ### DynamoDB Local
I successfully ran a dynamodb local container

![Image](images/dynamodbLocal.jpg)


- ### Postgres Container
I successfully ran a postgres container

![Image](imges/postgresContainer.jpg)

## Homework Challenges
- ### Pushing a tagged Image to Dockerhub
I tagged my frontend image as 1.0 and pushed it to Docker Hub. Here's a [Link](https://hub.docker.com/r/chxnedu/cruddur-frontend) to the image

- ### Implementing Healthchecks
I was able to implement a healthcheck for my frontend and backend conatainer in my [Docker Compose File](https://github.com/Chxnedu/aws-bootcamp-cruddur-2023/blob/main/docker-compose.yml)

![Image](images/healthcheck.jpg)

- ### Running Docker on EC2
I launched an EC2 Instance, installed Docker on it, and was able to pull the frontend image I committed to Docker Hub earlier

![Image](images/dockerPull.jpg)


