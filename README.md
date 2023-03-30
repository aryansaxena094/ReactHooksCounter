# React Hooks Counter

This is a simple ReactJS project that demonstrates the use of React Hooks to create a counter. It includes two components, index.js and App.jsx.

## Components

- index.js
This file is responsible for rendering the App component on the DOM. It imports the ReactDOM library, the App component from the App.jsx file, and then it calls the ReactDOM.render() method to render the App component on the HTML div element with the root ID.

- App.jsx
This component is the main component of the application. It uses the useState hook from React to create a state variable called count and a function called setCount to update it. It renders the current value of count along with two buttons, one to increase the count and one to decrease it. The increase and decrease functions update the count state using the setCount function.

## Usage
To use this project, you can follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running the `npm install` command in your terminal.
3. Run the project by running the `npm start` command in your terminal.
4. Open your browser and navigate to `http://localhost:3000`.
5. You should see a counter with two buttons that allow you to increase and decrease the count.

## Conclusion

This is a simple ReactJS project that demonstrates the use of React Hooks to create a counter. It can be easily customized and extended to fit your needs. The project is a good starting point for anyone who wants to learn React Hooks or create a simple counter application.