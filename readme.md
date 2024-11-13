# Hello World Project in Node.js Language

This is a basic "Hello World" project in the Node.js programming language. We will use Docker to create a container for the program, and Railway to deploy the project in the cloud.

## Prerequisites

It is required to verify the installation of Node.js on your computer. To check, open a terminal and run:

```bash
node --version
```

If Node.js is not installed, download it from [https://nodejs.org/](https://nodejs.org/).

## Clone the Project

1. Locate a folder of your choice and clone the project with the following command:

    ```bash
    git clone https://github.com/Karen020701/aplication-node.git
    ```

2. To run the project locally, navigate to the project folder and execute:

    ```bash
    npm start
    ```

3. Then, in your browser, go to [http://localhost:3000](http://localhost:3000). You should see the message: **"Hello World node language"**.

## Running with Docker

To run this project in a Docker container:

1. First, pull the Docker image. In the project directory, download the image with the command:

    ```bash
    docker pull karenchicaiza/aplicationode
    ```

2. To start the container, use the command:

    ```bash
    docker run -p 3000:3000 karenchicaiza/aplicationode
    ```

3. In your browser, go to [http://localhost:3000](http://localhost:3000) and you will see the message: **"Hello World node language"**.

## Deployment on Railway

This project has been deployed on Railway. The Railway account was connected, and access to the GitHub repository was configured. Once deployed, the following link was generated:

[https://aplication-node-production.up.railway.app/](https://aplication-node-production.up.railway.app/)


![image](https://github.com/user-attachments/assets/081acf7e-50a8-4828-bb03-c4c8833ebf3c)
