## SPA application

#### Front-end

- [ReactJS](https://reactjs.org/) - Frontend framework
- [useState hook & props](https://reactjs.org/docs/hooks-state.html) - For state management
- [React Router](https://reactrouter.com/) - For general routing & navigation
- [Semantic-UI w/ normal CSS for customisations](https://react.semantic-ui.com/) - UI library
- [React toast notifications](https://jossmac.github.io/react-toast-notifications/) - For toast notifications 

#### Back-end

- [Node.js](https://nodejs.org/en/) - Runtime environment for JS
- [Express.js](https://expressjs.com/) - Node.js framework, makes process of building APIs easier & faster
- [MongoDB](https://www.mongodb.com/) - Database to store document-based data
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling for Node.js
- [Cloudinary](https://cloudinary.com/) - For image uploading & related API
- [JSON Web Token](https://jwt.io/) - A standard to secure/authenticate HTTP requests
- [Bcrypt.js](https://www.npmjs.com/package/bcryptjs) - For hashing passwords
- [Validator.js](https://www.npmjs.com/package/validator) - For validation of JSON data
- [Mongoose Unique Validator](https://www.npmjs.com/package/mongoose-unique-validator) - Plugin for better error handling of unique fields within Mongoose schema
- [Dotenv](https://www.npmjs.com/package/dotenv) - To load environment variables from a .env file

## Features

- Authentication (login/register with email-password)
- Upload images for display pictures of contacts
- Add/update/delete contacts & change display picture
- Add/update/delete profile links of individual contacts
- Search contacts by name or profile links
- Toast notifications for actions - adding/updating/deleting contact, or welcome message etc.


## Usage


#### Env variable:

Create .env file in server directory and add the following:

```
MONGODB_URI = "Your Mongo URI"
PORT = 3005
SECRET = "Your JWT secret"
CLOUDINARY_NAME = "From your cloudinary dashboard"
CLOUDINARY_API_KEY = "From your cloudinary dashboard"
CLOUDINARY_API_SECRET = "From your cloudinary dashboard"
UPLOAD_PRESET = "Folder/preset name from your cloudinary account" (OPTIONAL)
```

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
