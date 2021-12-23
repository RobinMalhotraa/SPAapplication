## SPA application

#### Front-end

- ReactJS - Frontend framework
- React Router - general navigation and routing
- Semantic-UI for the UI library
- React toast notifications to receive toast notifications

#### Back-end

- [Node.js]for JS runtime environment
- [Express.js]for The Node.js framework simplifies and accelerates the process of developing APIs.
- [MongoDB] for Document-based data is stored in a database.
- [Mongoose] - Node.js object modelling for MongoDB
- [Cloudinary] - For image uploading and other related APIs
- [JSON Web Token]- A protocol for securing and authenticating HTTP requests.
- [Bcrypt.js] - For password hashing
- [Validator.js] - For JSON data validation
- [Mongoose Unique Validator]- Plugin for improved error handling of Mongoose schema's unique fields.
- [Dotenv]- Loading environment variables from a.env file

## Features

- Authentication (email-password login/registration) 
- Upload photographs for contact pictures to be shown. 
- Change the display picture and add/update/delete contacts. 
- Individual contact profile links can be added, updated, or deleted. 
- Contacts can be found using their names or profile links. 
- Toast notifications for actions such as adding, updating, or removing contacts, or sending a welcome message, among others.


## Usage


#### Env variable:

Create .env file in server directory and add the following:


#### Client:

Open client/src/backendUrl.js & change "backend" variable to `"http://localhost:3005"`

```
cd client
npm install
npm start
```

#### Server:

Note: Make sure that you have installed 'nodemon' as global package.

```
cd server
npm install
npm run dev
```
