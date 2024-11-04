# GetAI

### Install dependencies if you want to build this website from scratch

#### Client:
  ```sh
  npm install @emotion/react @emotion/styled @mui/icons-material @mui/lab @mui/material axios file-saver react-lazy-load-image-component react-router-dom  styled-components
  ```

#### Server:
  ```sh
  npm install cloudinary cors dotenv express mongoose nodemon openai
  ```
  
### To run file locally on your computer follow the steps

* Client:
```sh
npm start
```
* Server:
Install nodemon globally
```sh
npm i -g nodemon
```
```sh
nodemon app.js
```
```sh
node index.js
```

* Set environment variables in server and connect to mongo DB
```sh
MONGODB_URL=""
OPENAI_API_KEY=""
CLOUDINARY_CLOUD_NAME=""
CLOUDINARY_API_KEY=""
CLOUDINARY_API_SECRET=""
```
