Steps to create the Project

Step 1: creating a project folder.

mkdir restaurant-app
cd restaurant-app

Step 2: Backend Setup

Create folder within restaurant-app folder i.e. server

mkdir server 
cd server

Step 3: Initialize the Express project and install the required dependencies.

npm init -y
npm i express cors mongoose

Folder Structure(Backend):

<img width="311" height="162" alt="image" src="https://github.com/user-attachments/assets/e95ee532-6ab1-4cf5-9a89-a9c6c53fd0cf" />

Step 4: Initialize the frontend app and install required dependencies.

npx create-react-app client
cd client
npm i axios

Project Structure (Frontend):

<img width="392" height="786" alt="image" src="https://github.com/user-attachments/assets/05b9f1fe-cb5c-401b-bbba-2b1630ba7f5e" />

Step to Run the code by typing the following command

Start the backend:

node server.js

Start the frontend:

npm start

Output:

<img width="1090" height="700" alt="image" src="https://github.com/user-attachments/assets/23a23cde-85c0-4ebb-ac8d-865d000b700f" />
