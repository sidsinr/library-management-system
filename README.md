# Library Management System

A website to help a librarian manage all the information related to a library.\
Uses Firebase for authorization and Firestore as database. 

Use these login credentials: 
```
Email: testadmin@library.com
Password: testpassword
```


### [Live Demo](https://libmgmtsys.netlify.app)


### Screenshots
<img src="https://user-images.githubusercontent.com/118676744/224053940-3e851360-eed2-4493-8e8e-a5ebd3218308.png" width=70% height=70%/>
<img src="https://user-images.githubusercontent.com/118676744/224054978-615ba72a-0ef2-4b04-940e-507dc12d4a8c.png" width=70% height=70%/>
<img src="https://user-images.githubusercontent.com/118676744/224054801-02fdbdf0-f9d0-458c-9b3d-e5f277656b8e.png" width=70% height=70%/>
<img src="https://user-images.githubusercontent.com/118676744/224056974-42769106-7d1f-4bbe-8fad-d5455f53b4eb.png" width=70% height=70%/>
<img src="https://user-images.githubusercontent.com/118676744/224057181-c4f783c1-a6a9-4cfa-a398-1b276a8a5251.png" width=70% height=70%/>


## Features

- Admin login (firebase authorization).
- Add, edit and delete books.
- Add, edit and delete members.
- Book availability status.
#### Future plans

- More responsive table with sorting and searching.
- Use images. Add description card with details.
- Book issue/return portal, linking members and books database.
- Automatic calculation of fines on return default.

### Note! 

Since this demo is public, realtime syncing of data with the firestore database is not implemented. This project reads the data from the firestore database only once on first render and stores it in the `booksData` and `membersData` state. Changes are made to these states. 
## Built With

- ReactJS
- Firebase
- Material UI 
- React router


## Environment Variables

To run this project, you will need to add the following environment variables to your `.env` file

```
REACT_APP_FIREBASE_API_KEY
REACT_APP_AUTH_DOMAIN
REACT_APP_PROJECT_ID
REACT_APP_STORAGE_BUCKET
REACT_APP_MESSAGING_SENDER_ID
REACT_APP_FIREBASE_APP_ID
```


## Available Scripts
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).\
In the project directory, you can run:

- `npm start` : Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

- `npm test` : Launches the test runner in the interactive watch mode.

- `npm run build` : Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

- `npm run eject` : If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).


## License

[MIT](https://choosealicense.com/licenses/mit/)
