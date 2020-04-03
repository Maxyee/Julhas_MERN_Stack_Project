# MERN Shop
This project is basically divided into two part one is frontend and another is backend. However earlier I mentioned my work
process as well as achitecture. Now I implemented a simple SPA application using `ReactJS` and `ExpressJS` both are running 
on the `NodeJS` runtime. I did not use any mongoDB database here. On my next project, I will use the MongoDB database too.

## Frontend Installation
For running this project, we need to run two project separetly from two different terminal. Lets start the frontend part 
first then we will run the backend part. Fronted is created with `ReactJS` and I added all the package into the `Package.json` file. Thus, we need to run some command for running this project, all of the commands are mentioned below :

At first we need to install the `NodeJs` into our machine. Then go the frontend folder. After navigating the frontend folder
simply type command into you `terminal` for Linux/ `command propmt` for windows user.

`npm install`

This command will download all of the node-modules package into our project. After that, run another command

`npm start`

Now we will see that our development server is running for frontend react into the port 3000 

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### My install process frontend

Screenshot is given for better understanding, how I start my development server.

![alt text](https://github.com/Maxyee/Julhas_MERN_Stack_Project/blob/master/shotsPart2/frontendNPM.png)

After completing the install process then run another command `npm install`

Finally, opening the browser and I get this UI .

![alt text](https://github.com/Maxyee/Julhas_MERN_Stack_Project/blob/master/shotsPart2/beforeAddProduct.png)


## Backend Installation
For running the backend server, At first, I switched to backend folder and then ran this following command through
my vs code IDE terminal

`npm install`

This command will download all of the node-modules package into our project. After that, run another command

`npm start`

Now we will see that our development server is running for frontend react into the port 5000. Because into the `server.js`
file I initialize the port number 5000 . below screenshot will help us to better understand.


![alt text](https://github.com/Maxyee/Julhas_MERN_Stack_Project/blob/master/shotsPart2/InitializePort.png)

Open [http://localhost:3000](http://localhost:5000) to view it in the browser. From that url we will define our API 
endpoints

### My install process backend

Screenshot is given for better understanding, how I start my backend development server.

![alt text](https://github.com/Maxyee/Julhas_MERN_Stack_Project/blob/master/shotsPart2/backendNPM.png)

After completing the install process then run another command `npm install`

Finally, opening the browser with my frontend project which is running in the port 3000. Therefore, now I can add my project
into the project. Before starting my backend server I can not add any project into my frontend side. Now I can do it because
my backend server is running and the data is successfully responsed by the express server.

![alt text](https://github.com/Maxyee/Julhas_MERN_Stack_Project/blob/master/shotsPart2/afterAddingProduct.png)

