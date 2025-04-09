In this DevOps task, you need to build and deploy a full-stack CRUD application using the MEAN stack (MongoDB, Express, Angular 15, and Node.js). The backend will be developed with Node.js and Express to provide REST APIs, connecting to a MongoDB database. The frontend will be an Angular application utilizing HTTPClient for communication.  

The application will manage a collection of tutorials, where each tutorial includes an ID, title, description, and published status. Users will be able to create, retrieve, update, and delete tutorials. Additionally, a search box will allow users to find tutorials by title.

## Project setup

### Node.js Server

cd backend

npm install

You can update the MongoDB credentials by modifying the `db.config.js` file located in `app/config/`.

Run `node server.js`

### Angular Client

cd frontend

npm install

Run `ng serve --port 8081`

You can modify the `src/app/services/tutorial.service.ts` file to adjust how the frontend interacts with the backend.

Navigate to `http://localhost:8081/`
![image](https://github.com/user-attachments/assets/603f5e1e-04c1-4d35-b3e1-b8c4524cfaee)
![image](https://github.com/user-attachments/assets/b66b2e8b-5f96-4af1-9cb7-06b7d255353f)
![image](https://github.com/user-attachments/assets/75a62eab-4fc9-41b7-ac7f-84fe0e94f811)
![image](https://github.com/user-attachments/assets/5dec2973-b926-42d3-99f3-b343b68a4972)
