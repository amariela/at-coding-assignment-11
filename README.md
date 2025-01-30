# Coding Assignment 11


## Instructions for running the app

1. Open a local terminal.

2. Pull the image from docker:

    `docker pull elacodes1/teodocio_aena_coding_assignment11`

3. Run the image:

    `docker run -p 7775:80 elacodes1/teodocio_aena_coding_assignment11`

4. In a local browser, head to `http://localhost:7775/`


## About the assignment

I did the following:

- Built an app using the create-react-app feature.
- Created a Dockerfile with a multi-step build (build and production stage). This reduces the image file size, reduces the build time because dependencies and Node.js is not included during runtime, and uses Nginx to serve a static files.
- Create an image and containerize the image using Docker "build" command.

- Use Docker Compose to configure the app as a service (useful for hot reloading).
- Push, pull, and run a Docker image from Docker Hub.