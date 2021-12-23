## SPA application

#### Front-end

- [ReactJS](https://reactjs.org/) - Frontend framework
- [useState hook & props](https://reactjs.org/docs/hooks-state.html) - for the purpose of state administration
- [React Router](https://reactrouter.com/) - general navigation and routing
- [Semantic-UI w/ normal CSS for customisations](https://react.semantic-ui.com/) for the UI library
- [React toast notifications](https://jossmac.github.io/react-toast-notifications/) to receive toast notifications

#### Back-end

- [Node.js](https://nodejs.org/en/) for JS runtime environment
- [Express.js](https://expressjs.com/) for The Node.js framework simplifies and accelerates the process of developing APIs.
- [MongoDB](https://www.mongodb.com/) for Document-based data is stored in a database.
- [Mongoose](https://mongoosejs.com/) - Node.js object modelling for MongoDB
- [Cloudinary](https://cloudinary.com/) - For image uploading and other related APIs
- [JSON Web Token](https://jwt.io/) - A protocol for securing and authenticating HTTP requests.
- [Bcrypt.js](https://www.npmjs.com/package/bcryptjs) - For password hashing
- [Validator.js](https://www.npmjs.com/package/validator) - For JSON data validation
- [Mongoose Unique Validator](https://www.npmjs.com/package/mongoose-unique-validator) - Plugin for improved error handling of Mongoose schema's unique fields.
- [Dotenv](https://www.npmjs.com/package/dotenv) - Loading environment variables from a.env file

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
