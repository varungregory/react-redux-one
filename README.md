React Redux tutorial.
https://www.youtube.com/watch?v=OxIDLw0M-m0&list=PL4cUxeGkcC9ij8CfkAY2RAGb-tmkNwQHG

React Redux with Firebase
https://www.youtube.com/playlist?list=PL4cUxeGkcC9iWstfXntcj8f-dFZ4UtlN3

React CDN
https://reactjs.org/docs/cdn-links.html

Firebase
https://firebase.google.com/


<script crossorigin src="https://unpkg.com/react@16/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>

<script crossorigin src="https://unpkg.com/react@16/umd/react.production.min.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@16/umd/react-dom.production.min.js"></script>

Componenets installed in VSCode
- ES7 React/Redux/GraphQL/React Native Snippets
- Sublime Babel
- Monokai ++ Theme
- Live Server

Chrome extension
- React developer tools : https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en

NodeJS :
- Go to nodejs.org
- download the latest version (10.13.0.lts)


https://github.com/iamshaunjp/react-redux-complete-playlist.git
https://github.com/iamshaunjp/react-redux-complete-playlist.git


https://github.com/varungregory/react-redux-one.git


When should a function be declared as an arrow function
=======================================================
If we need to use the this keyword inside our javascript functions then the functions
have to be declared as arrow functions. for e.g.

handleMouseOver = (e) => {
    console.log (this.state.name)
}

instead of 

handleMouseOver(e){
}



Steps to create a react app
===========================
- https://github.com/facebook/create-react-app
- npx create-react-app myapp
- cd myapp
- npm start
- npm install react-router-dom  ( this is to install react router dom in projects where routing has to be done among multiple
  templates)
- npm install axios 
- npm install redux react-redux 
- npm install redux-thunk
- npm install firebase
- npm install react-redux-firebase redux-firestore
- npm install moment // this is for formating dates etc.

Packages installed for Udemy Course
- npm install --save radium 
  ( react package for inline style with psuedo selectors and media queries.  --save will add entry into package.jason )
- npm run eject (eject from package manager updating configuration files each time npm install is executed)
- npm install --save prop-types 
  (library to set up validation for incoming prop values)
- npm install --save axios
- npm install --save react-router react-router-dom
  We installed both react-router  and react-router-dom . Technically, only react-router-dom  is required for web development. 
  It wraps react- router  and therefore uses it as a dependency. 

Two types of components in React
================================
- UI Component : UI component are function based components that does not need a state.  Its purpose is to receive props
  and present it in the user interface.  function base templates/components will not have a render() method.
- Container Component  : Container components are class based componets that have a state. class based components will have a render()
  method


Materialized CSS CDN
--------------------
https://materializecss.com/getting-started.html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0-rc.2/css/materialize.min.css">    

Fake API Calls URL
==================
https://jsonplaceholder.typicode.com/
- /posts 	100 posts
- /comments 	500 comments
- /albums 	100 albums
- /photos 	5000 photos
- /todos 	200 todos
- /users 	10 users

Usefull resources
=================
- Generate CSS Spinners : https://projects.lukehaas.me/css-loaders/
- CodePen : Codepen.io
- Firebase : firebase.google.com


