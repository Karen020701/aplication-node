**Hello World” project in Node.js language**  
This is a basic project of a “Hello World” in Node.js language, we are going to use Docker to create a container of the program and Railway is used to deploy the project in the cloud.  

It is required to verify the installation of the Node.js extension on the computer, this is done by accessing to the computer and running the command node --version otherwise if you don't have it go to the page https://nodejs.org/ and download it.  

**Clone the project**  

Locate in a folder of preference to be able to clone the project with the following command:  
https://github.com/Karen020701/aplication-node.git  
To run the project locally, navigate to the project folder and run the command:  
npm start  

In the browser enter http://localhost:3000 and the message “Hello World node language” will be displayed.  

**Running with Docker**  
An image is built in Docker. Once inside the directory to download the created image run the command:  
docker pull karenchicaiza/aplicationode  

To run the container the command is used:  
docker run -p 3000:3000 karenchicaiza/aplicationode  

In the browser enter http://localhost:3000 and the message “Hello World node language” will be displayed.  

**Deployment on Railway**  
This project was deployed in Railway, the connection of the Railway account and access to the repository in Github was done.   
Once deployed I generate the link: https://aplication-node-production.up.railway.app/

![image](https://github.com/user-attachments/assets/081acf7e-50a8-4828-bb03-c4c8833ebf3c)
