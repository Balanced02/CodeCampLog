### Wednesday, 28th June, 2017
==================================================================================
+ Recaped Javascript as a Document Object Model of an actual HTML
+ Did an example using some javascript keywords like function, alert, onclick
+ Altered that same example to use jQuery library
+ Learnt about git(software), & github(website)
+ Uploaded my first Portfolio Work on github
+ Downloaded one of Mr. Ebuka's repositories and it looked #awesome
+ Planning on ...

### Thursday, 29th June, 2017
==================================================================================
+ Worked intensively on my Portfolio
+ Learnt how to clone from github
+ Learnt how to push back to github after effecting corrections
+ Finished the introToWebDev video

### Friday, 30th June, 2017
==================================================================================
#### Had an official innauguration ceremony 
##### Things learned from the ceremony
##### Mr. Ebuka Anichebe
+ It's not about your ability to code, but what can you make to affect the society
+ We're supposed to be solving the data/statistical issues in the Nigerian economy... case study of our Nigerian government systems
+ Give yourself a challenge... and make it happen
- What people look out for before giving you money
+ Competence
+ Emotional Competence (How do you get along with people)
> There's a difference between an in-depth project management/busienss analyst and personal project management... For a start, the need for a project manager is not necessary, but when already established, spliting the management and the coders would be necessary
#### Normal log for the day
+ Learnt extensively on css styling, flex box
+ Worked on my portfolio

### Saturday, 1st July, 2017
==================================================================================
#### Videos Collected
+ Learnt about some new tags like blockquote, code etc.
#### Javascript Videos from Scotch.io
+ Learnt how to get data from form input
+ Learnt how to manipulate data gotten from form input

### Sunday, 2nd July, 2017
==================================================================================
### PortFolio Page
+ Added time display
+ Changed the top background pic
### Javascript Videos from Scotch.io
+ Going nice so far... just still learning, haven't applied yet... 

### Mondaay, 3rd July, 2017
==================================================================================
+ Learnt how to get form input and manipulate them using JavaScript
+ Learnt how to perform same operation using jQuery
+ Learnt the new Date() function and how to get hours, minutes and manipulate them
+ Solely learnt partially how to read docs from mdn and apply them

### Tuesday, 4th July, 2017
==================================================================================
+ Learnt about switch statements and used it to solve an algorithm I originally used if statement to solve
+ Thanks to beta.fcc, recalled how to access object properties using the dot and bracket notations
+ Learnt how the setInterval works and read part of the docs on it from mdn
+ Learnt more about the function Date() and implemented it with others for a countdown timer

### Wednesday, 5th July, 2017
==================================================================================
+ Learnt the difference and similarities between document.querySelector() and document.getElementById()
    - The functions getElementById and getElementsByClassName are very specific, while querySelector and querySelectorAll are more elaborate.
    - QuerySelector is the newer feature.
    - QetElementById is better supported than querySelector.
    - QuerySelector is better supported than getElementsByClassName.
    - QuerySelector lets you find elements with rules that can't be expressed with getElementById and getElementsByClassName


#### PROJECT IDEAS

+ Vehicle authentication system
- uses their Chasis No.
- collects detailed info on the vehicle and vehicle's owner
- updates details on any changed item that changes the physical properties of the vehicle
+ Virtual Reality for educational purposes
+ Contact form that sends the details to your personal mail... 
- give clients a javascript link and it generates a form on their page; when user fills, and submits, the info comes to your platform and you send the details to the client...
> Build an api, build a product on that api, sell the core api to others to build product on, and you'll be a top competitor
+ Online bookstore for Nigerian books
+ Build an incentive system, like 2go stars
+ Platform for teachers, mentors and trainers to be able to deliver tests and surveys for their classes
	- Generates more exams and tests
	- Faster compilation of results are gotten
	- Paid items like auto grading, statistical grading and reports on each student
	- Survey for parents & guidance and generate reports to dispatch to them
	- Teacher's dashboard to see summary of everything going on
	- Generates tokens to studenst you want to take the test
	- Companies can use it for interviews and to test candidates (Aptitude Tests)
+ Replica of survey monkey
	- Administers surveys/questionnaires to anyone in the world
+ Substitute for Google Forms that adds more functionality/value to form collection
	- Google forms don't have document uploads, passport uploads, just tests
+ Barcode to pay money for faster transactions
+ E-commerce platform that includes people without internet
+ Social Bet sites
+ Enterprise Resource Planning software
    - Human Resource, Bank, Pay Roll
+ E-learning management system, Facility management system
+ To-Do list with countdown timer and alarm/alert when due

### Thursday, 6th July, 2017
==================================================================================
+ Learnt about scope
+ Learnt and understood better recursion

### Friday, 7th July, 2017
==================================================================================


### Saturday, 8th July, 2017
==================================================================================
+ Learnt about React-Native
+ Set up my Android Studio
##### Starting a new project on React-Native
+ go to the folder you wanna do the project in your terminal
- react-native init weCodeApp2
- npm install
- open your android studio and get the emulator on
- react-native run android // it'll load the embedded server and download some apps, you'll need internet for your first running
- by default, it has an android folder// you can write your codes in the java file under /android/app/src/main/java/com/wecodeapp2
- by default, it runs in debug mode // so you'll need to build a signed key and embed it in your java
- it's better to write your app in another folder application/component directory //you'll need to create it
- you can also create another folder assets under application where you can store your images, css files and others...
- command d//reloads ios emulator
- RR //reliads android emulator
- NB: you can enable live reload & hot reload on the emulator; an advantage of react-native over native stuffs
- You can edit the native first page of a react-native app by editing index.android.js file

### Monday, 10th July, 2017
==================================================================================
+ Learnt and used the reduce, filter and map functions
+ Started learning ES6 Module on beta.fcc
+ Learnt that the "use strict"; was to avoid use of undeclared variables.

### Tuesday, 11th July, 2017
==================================================================================
+ Introduced Nodejs
+ Learnt how to import and export using nodejs

### Wednesday, 12th July, 2017
==================================================================================
+ Started a Todo App
+ Learnt how to change css styles using jQuery

### Thursday, 13th July, 2017
==================================================================================
+ Learnt .empty() .append() manipulating the dom using jQuery
+ Learnt a little more about map and filter

### Friday, 14th July, 2017
==================================================================================
+ Continued my todo App to some extent
+ Learnt how to use jQuery in adding or removing CSS classes

### Saturday, 15th July, 2017
==================================================================================
+ Re-did the todo App with some of my mates and understood some basic javascript concepts explicitly

### Sunday, 16th July, 2017
==================================================================================
+ Faced the tasks at repl.it and I'm almost done
+ Learnt about parseInt/parseFloat and str.substring methods

### Monday, 17th July, 2017
==================================================================================
+ const express = require('express'); require keyword to import express which is in bracket

+ const app = express()//initialize express with an app variable

+ app.listen(3000, function(){
	console.log('Your express server is now running on port 3000') //to display on your server console not browser console
}) //app.listen takes a listen port number and localhost address, the localhost is optional

+ app.get('/', function ()....) //takes a string which represents a route you wanna handle for... / means home or homepage. every express route handler takes two values which are req (request object) and res (response object)

+ the request object (req) usually contains the information the client sends along with the get request, things like browser info, data sent to the server

+ the response object (res) contails the methods to format/determine the type of information sent to the client

+ http://localhost:3000/ after the : the number is the port number, if there isn't any number there, the default port is 80 for most web pages

+ res.redirect('/profile') //redirect a user to /profile route


### Tuesday, 18th July, 2017
==================================================================================
+ app.post() // api endpoint

+ ETag:W/"818-15d46f2e9d8" //what the browser uses to know if the file has been changed hence a 304 message (Not Modified) or 200 (Ok/from disk cache/from memory cache)

+ body-parser // handles forms - Node.js body parsing middleware. Parse incoming request bodies in a middleware before your handlers, available under the req.body property.

+ npm install nodemon -g //utility that auto-restarts the node when there's any change

+ nodemon index //to run instead of node index

### Wednesday, 19th July, 2017
==================================================================================
+ app.get('/show/:id', (req, res) => { // :id colon and value (request parameter)

+	state = req.params.id // accessing the id from the request.params.id

### Thursday, 20th July, 2017
==================================================================================
+ Re-did the server side of the todo app and corrected the filtering functions

### Friday, 21st July, 2017
==================================================================================
+ Read about set and understood about adding to set and checking set length

### Saturday, 22nd July, 2017
==================================================================================
+ Learnt about Mongodb - that it is a NoSql database (doesnt have a fixed structure)
+ .find(), .update(), .createUser(), .createCollection, .insert(), .remove()

### Sunday, 23rd July, 2017
==================================================================================
+ Finished the repl.it test

### Monday, 24th July, 2017
==================================================================================
+ Learnt about using full bootstrap classes in creating a webpage instead of hacking the css ourselves

### Tuesday, 25th July, 2017
==================================================================================
+ Learng about ejs (embeded javaScript) a html format where you can embed javascript codes using <%=...%>
+ Learnt about sending routes from a server to another file to haldne
+ Learnt the difference in importing and exporting files and modules

### Wednesday, 26th July, 2017
==================================================================================
+ Learnt about mongoosejs, created a cloud database with mlab, connected to it, learnt about promises
+ When we wait for an action to complete, we can use primises, callbacks or async //more research on async to be made
+ When you have to wait for something or not instant, you either use a promise, async or callbacks...

+ Promise = .then(); .catch(err) both takes a function that occurs when either it's fulfiled (then) or error (.catch)

+ Every query returns a promise

+ An empty query returns all data

### Thursday, 27th July, 2017
==================================================================================
+ Learnt about validation using mongoosejs, minimum, maximum, required and enum
	- Min and Max for numbers to specify allowed entries
	- Maxlength and Minlength for strings
	- enum specifies set of allowed entries
	- match specifies set of regular expression a string must match
	- required...

### Friday, 28th July, 2017
==================================================================================
+ Added update post, and search functionalities to KoldedLand

### Saturday, 29th July, 2017
==================================================================================
+ Added the registration form, handled form validation of username and passwords... yet to validate email

### Sunday, 30th July, 2017
==================================================================================
+ Login portal now working
+ Deletepost and update post now only shows if logged in

### Monday, 1st August, 2017
==================================================================================
+ Updated registration form of Koldedland
+ Learnt about loadash (_.pick) to get form values

### Tuesday, 2nd August, 2017
==================================================================================
+ Learnt more about bootstrap, grid system, jumbotron

### Wednesday, 3rd August, 2017
==================================================================================
+	React has JSX (a html-like syntax that can be written in javascript)
+	You can write your app as components...
> Function cannot maintain state
+ Class in javascript are objects that does something
+ extends - more like prototype chaining... class TodoApp extends React.Component i.e. TodoApp will inherit many things from the basic react component
+ What makes React better is it's state management... Every react component can have a state (a data store or a way to store data).
+ To write javascript in JSX, you wrap it in curly braces
+ Class can maintain state, while functions are stateless components
+ all JSX must be wrapped together in a tag... best practice, a div... adjacent tags are not allowed
+ this.setState({object}) //changes the value you wanna change
+ this.setState((prevState) => { }) //passes the previous state to the function then change...
+ ReactDOM.render(<App />, document.getElementById('root')); takes two values... react component you want to render and where you want to render it
+ Class is a reserved word in javascript... so, you can't use html classes instead, we use className (class in html === className in react JSX)
+ React has autoreload at each save instance
+ mkdir to make a directory (folder)
+ touch src/index.js to create a file
+ class ShoppingList extends React.Component {...} every react extends from React.Component
+ props is a way parent component pass data to the child component
+ function Square({iClick, value}) // object destructuring... specifying only the keys you need to be passed into the function from the object...

### Saturday, 5th August, 2017
==================================================================================
+ Learnt about async functions like setTimeout() and callbacks

### Sunday, 6th August, 2017
==================================================================================
+ Learnt about find and FindOne - Find returns an object while findone returns an array in Mongodb
+ Just read a bit about jade

### Monday, 7th August, 2017
==================================================================================
+ Started re-definition of some JavaScript native functions

### Tuesday, 8th August, 2017
==================================================================================
+ Installed JsonView extension for viewing json objects in browser in a much nicer/clean form
+ JSON.stringify(body, filter, formatspaces) // JSON.stringify(object, undefined, 2)
+ Setting default values when creating a function e.g. function (val = 0) //sets val to 0 if it was called without passing any value
+ React-Native style = ({backgroundColor: '#34495E'}) 

### Wednesday, 9th August, 2017
==================================================================================
+ Redux is used for state management instead of managing state individually
+ Every redux action needs a type

### Thursday, 10th August, 2017
==================================================================================
+ Usin request npm module to send and receive json response

### Friday, 11th August, 2017
==================================================================================
#### MR. TEMITOPE PAULSON
> An Entrepreneur sees a need, and creates solution to them
+ Benefit: You must be clear on the benefit your product provides...
+ Target Market: Who buys from you and how you can make their lives better...
+ USP (Unique Selling Proposition)
#### Competitive Advantage
+ Cost Leadership: Provide reasonable value at lower price
+ Differenciation (keyword: Innovation): Delivering value better than anyone else
+ Focus: Understanding and servicing your target market better than anyone else...
> Repitition is the law of deep and lasting impression (10,000 hrs to mastery)

#### Selling
+ Process where sales professionals convince a prospect to buy a good
> No matter how passionate or eloquent a salesperson you may be, no matter how friendly your smile or likeable your personality, if you can't close the sale, your efforts yield nothing
- Golden Nugget

### Saturday, 12th August, 2017
==================================================================================
+ Started a Todo App with React
+ Working on a Bible App

### Thursday, 17th August, 2017
==================================================================================
+ Styling in React native uses camelCases instead of dashes of CSS and often used as an object

### Friday, 18th August, 2017
==================================================================================
+ Fix issue with stucking at Starting Packager... sudo sysctl -w fs.inotify.max_user_watches=10000

### Monday, 21st August, 2017
==================================================================================
+ sudo mongod --dbpath /home/balanced02/data/db
+ Life cycle methods are functions automatically called at some point on a class that mounts the component once it's called // example comoponentWillMount

### Tuesday, 22nd August, 2017
==================================================================================
+ npm module - axios //to make http request
+ passport.serializeUser goes to the database and get the user object
+ passport.deserializeUser appends the user object to request

### Wednesday, 23rd August, 2017
==================================================================================
+ ComponentState: State is how React handles changing the content that shows on the screen
+ Did a Staff List page on React and achieved pagination
+ Added NewOrder api to Laundry-Express

### Thursday, 24th August, 2017
==================================================================================
+ By default, fetch does not send cookies, so we initialize credentials: 'include' in the options object

### Saturday, 26th August, 2017
==================================================================================
+ Make a product of your idea, get feedback from users and iterate
+ Docker installation [Docker Installation Link](https://docs.docker.com/engine/installation/)
+ [Docker Repository](https://hub.docker.com) for storing your images on the cloud

### Sunday, 27th August, 2017
==================================================================================
+ Accessing props from class component = this.props.
+ Accessing props from a functional component = props.

### Tuesday, 5th September, 2017
==================================================================================
+ Used nodemailer to send form details to email

### Wednesday, 6th September, 2017
==================================================================================
+ NODE_ENV usually a default process.env variable which results to either production, test or development
+ A closure is an inner function that has access to the outer (enclosing) function's variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function's variables, and it has access to the global variables.
+ passport.serializeUser checks the user cookies and goes to the database and to the user object
+ passport.deserializeUser appends the user object to request

### Thursday, 7th September, 2017
==================================================================================
+ Webpack + Babel to transpile all codes to a single ES5 file compatible for browsers
+ A component is a collection of Javascript functions that produce HTML
+ git remote add upstream [Link to forked project](https://github.com/Balanced02/CodeCampLog)
+ this in ES5 refers to the parent of where it's initialized/called (cause it lexically binds it to the function) while this in ES6 refers to the global object
+ Closure is a function that remembers it's scope after calling it
	```javascript
		function closure(a) {
			return function (b) {
				return a * b
			}
		}
		var n = closure(3) // assigns the returned function to n
		calling n(5) //returns 15 since n maintains a closure over the original function so, it has access to the a variable in the original function
	```