# Netflix GPT

Movies recomandation with AI.

## Setup

- Install react app using create-react-app (CRA)

```js
npx create-react-app netflix-gpt
```

- Install and init tailwind css

```js
npm install -D tailwindcss
npx tailwindcss init
```

- Configure tailwind css in your project

  `npx tailwindcss init` command will create a file `tailwind.config.js` in your project's root directory.
  Open `tailwind.config.js` and replace all content with below code.

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

- Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

- Now you created a react app with tailwind css successfully. Now run the below command on your terminal to start your local development server.

```js
npm start
```

## Routes

- Home Page (is user !authorised)

  - Signin/Signup Page
    - SignInForm / SignUpForm

- Browse Page

  - Navbar
  - Showcase
  - Trendings
  - MoviesSuggestion
    - MoviesList \* N

- NetflixGPT
  - Search
  - MoviesSuggestion

## Features
1. Create React app
2. Tailwind Css
3. Header
4. Routing of App
5. Login Form
6. Sign up Form 
7. Form Validation
8. useRef Hook
9. Firebase
    - Connection
    - Deployment
10. Sign up user with firebase
11. Implement sign in with API
12. Created redux store with userSlice
13. Udpate profile and Sign Out
14. Bug Fixes: Sign up user displayName, profile picture, protecting unauthorized routes
15. Adding constants
16. Adding the TMDB API
17. Strict mode explaination
18. Custom hook for getting now playing movies
19. Use more TMDB Apis and build browse page
20. Search GPT
21. Multilingual search support
22. Protect keys
24. Making it responsive 

## Screen Shot

- Signin Page

  ![Signin Page](https://github.com/sahil123231/netflix-clone-react/blob/main/public/screenshot/01-signin.png)

- Signup Page

  ![Signup Page](https://github.com/sahil123231/netflix-clone-react/blob/main/public/screenshot/02-signup.png)

- Browse Page

  ![Browse Page](https://github.com/sahil123231/netflix-clone-react/blob/main/public/screenshot/03-browse.png)

- Movie List

  ![Movie List](https://github.com/sahil123231/netflix-clone-react/blob/main/public/screenshot/04-movieList.png)

- Search Page

  ![Search Page](https://github.com/sahil123231/netflix-clone-react/blob/main/public/screenshot/05-searchMovies.png)

- Movie results page

  ![Movie results](https://github.com/sahil123231/netflix-clone-react/blob/main/public/screenshot/06-movieSuggestions.png)

