React Redux tutorial.

https://www.youtube.com/watch?v=OxIDLw0M-m0&list=PL4cUxeGkcC9ij8CfkAY2RAGb-tmkNwQHG

https://reactjs.org/docs/cdn-links.html

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
