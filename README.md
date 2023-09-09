# WhatsApp Like Messenging Application

## React + Material UI

![Capturef](https://github.com/zulfiqar313/messaging-application/assets/69974518/e893b4b6-70d3-41bd-b6b0-c7d510a7a0e8)


### [Live Site](https://whatsapp-3bdd3.firebaseapp.com/)

## Usage

1. Create a `firebase.js` file in the project directory with the following code and add your own Firebase credentials within the single quotes:

   ```javascript
   import firebase from 'firebase';

   const firebaseApp = firebase.initializeApp({
     apiKey: '',
     authDomain: '',
     databaseURL: '',
     projectId: '',
     storageBucket: '',
     messagingSenderId: '',
     appId: '',
   });

   const db = firebaseApp.firestore();
   const auth = firebase.auth();
   const storage = firebase.storage();

   export { db, auth, storage };

```
## Install Dependencies
```
npm install
```

## Run App
```
npm start
```
```
