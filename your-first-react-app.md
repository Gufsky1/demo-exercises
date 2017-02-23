# Your first React app

#### Objective
Dive into creating a React app using create-react-app

#### Description
Students will use npm and the command line to install create-react-app and modify their first Page inside a single page application

#### Requirements
Requires a primer on NPM, command line execution, basic JavaScript module import/export, Chrome devtools usage

## Student instructions

Use NPM to install the create-react-app package globally.  Note: you may have to use sudo

```bash
npm install -g create-react-app
```

Navigate to your project folder.  Execute create-react-app and generate your app.  The name you give it will also be the folder it gets generated into.

```bash
create-react-app hello-world
```


Navigate to your app and start it.

```bash
cd hello-world
npm start
```

#### Examine app
  1. look inside /src folder
  2. find index.js
  3. traverse import statements

#### Edit app
  1. Open App.js
  2. Find the header and replace it with your name
  3. see changes in browser

#### Examine App in browser using chrome devtools
  1. open chrome devtools
  2. inspect an element
  3. use devtools to change the color of element

#### Edit CSS
  1. open App.css
  2. change App-header background color

## Create your first component 
  1. Create a file named Card.js
  2. Write a stateless functional component 
  3. Import Card.js in App.js
  4. Compose Card inside of the main App component

#### Add interaction
  1. Inside Card.js add a link to google
  2. test link, make sure it works

#### Change behavior of link
  1. add an onClick handler to link
  2. prevent the default behavior of the link
  3. add a console log to the handler
  4. open up chrome devtools and see your console log
  5. change console log to alert

#### Turn your link into a component
  1. in same file, create a new component
  2. rename component to Link
  3. move your link into component
  4. compose your Link inside of Card and inside of App (twice)

#### Pass properties to your Link components
  1. add an attribute to your first Link component called message
  2. inside your link component replace your alert message with your new prop value
  3. repeat for the second link
  4. replace your link text with the same method in steps 1-3


### Example trainer instructions & notes
1. walk students through
2. encourage students to attempt on own, facilitate by interacting with students

# ...shortened for brevity, this is a sample
