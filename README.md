# Disney Plus Clone
### Made by React JS

## Check It Out! :fire:
https://disney-plus-clone-d166f.web.app/

## Used
- Skills
```
React, Redux, styled Components, Firebase, Google Login
```
- firebase -v9 
```
//firebase.js
import { initializeApp } from "firebase/app";
import { getAuth, GoogleAuthProvider } from "firebase/auth";
import { getFirestore } from "firebase/firestore";
import { getStorage } from "firebase/storage";

const firebaseConfig = {
	//info
};

initializeApp(firebaseConfig);
const db = getFirestore();
const auth = getAuth();
const provider = GoogleAuthProvider();
const storage = getStorage();

export { auth, provider, storage };
export default db;
```

Install
```
- for image slider
npm i react-slick
npm i slick-carousel  

- styled Components
npm i styled Components

- redux
npm i @reduxjs/toolkit
```

## Screen Shot
#### Desktop
![ezgif com-gif-maker](https://user-images.githubusercontent.com/55618626/187279038-6eb09cab-c52e-49fa-a9d0-74aeb8cd9090.gif)



#### Responsive
![respo](https://user-images.githubusercontent.com/55618626/187277854-ee5acb57-a3a4-4b8c-ab58-7944bade21e3.gif)



## Folder Structure 
```
│  App.css
│  App.js
│  disneyPlusMoviesData.json
│  env.js
│  firebase.js
│  index.css
│  index.js
│
├─app
│      store.js
│
├─components
│      Detail.js
│      Header.js
│      Home.js
│      ImgSlider.js
│      Login.js
│      NewDisney.js
│      Originals.js
│      Recommends.js
│      Trending.js
│      Viewers.js
│
└─features
    ├─movie
    │      movieSlice.js
    │
    └─user
            userSlice.js
```
