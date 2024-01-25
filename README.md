# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)



# Project Details


Implemented a SPA mobile react/redux application for students to be used for student enrollment. Here is the behaviour of the mobile webapp. 

1. Page 1 - content looks like - 

Enter into Student Info System
[Button] Enroll Now!


2. Upon clicking on Enroll Now, a chatbot shows that takes up the screen looks like this.

Chatbot says - 

a.
... [for 3 seconds]

replaces .... with - Hello, Welcome to student info system! [It does this for all msgs bot types]

1 button says - Got it!

User clicks on "Got it!"

Got it! gets printed on Chatbot. So it looks like - 


Bot: Hello, Welcome to student info system!
User: Got it!

b. 	Bot then display a calendar strip and asks user to select one date from the 
calendar strip


Bot: Pick a slot !

User clicks on one of the option

Then bot displays time slot strip for morning, afternoon and evening

User selects one of the time slot 

User: 15 MAY, MON 11AM

For reference checkout below screenshot : 


c. Bot then asks for Name

B: Hello, Welcome to student info system!
U: Got it!
B: Pick a slot !
U: 15 MAY, MON 11AM
B: Enter your Name

[Label] That takes Name as input

User types Name and presses enter. Lets say - 


B: Hello, Welcome to student info system!
U: Got it!
B: Pick a slot !
U: 15 MAY, MON 11AM
B: Enter your Name
U: Gowtham

d. Bot asks and gets age from user. Age is a drop down. 18-40.

So overall after entering age, it looks 

B: Hello, Welcome to student info system!
U: Got it!
B: Pick a slot !
U: 15 MAY, MON 11AM
B: Enter your Name
U: Gowtham
B: Enter your Age
U: 27


e. Bot then says "Thank you. In 5 seconds, bot will exit" as the last line below 27. It counts down , 5..4...3..2...1 and then it takes user to page 3


3. Page 3 says - 

Your name Gowtham aged 27 has been added to student system. You may now exit.
