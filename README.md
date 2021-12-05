# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

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

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

### Project Description

The app is meant to have a map where is possible visualize the information for each state of the country having in mind the obtained information. When the application loads for the first time, it should be visualized the map with the information. The application should have a lateral menu, which contains a filter functionality to search though each state showing extra details.

### Solution Focus

The solution focuses on the front-end because am applying for a front end role

### Technical Choices and reasoning behind

1. React - I chose React because I am proficient with the library and super performant.
2. Diseases.sh API - I used this API instead of the one provided because the one provided was shut down in June 2021. Diseases.sh still had covid data in their platform.
3. Materia UI - Easier getting up and running with some of the already built in components such as Cards.
4. Chart Js - Offers a very easy way of implementing charts in React
5. Leaflet - I used this to generate the map functionality because am familiar with the technology and requires very little configuration to get up and running

### Tradeoffs

1. Mapping US states - I chose to use countries instead of states in the map implementation because state data was scarce to find and the API I found on countries had all the necessary data I needed for this project(including latitude and longitude coordinates).
2. Clicking on state and highlighting its border along with its details - I chose to use circles as indicators of countries and they differed in size depending on the the number of infections in a region. Instead of mapping a border when clicked, I implemented a pop up that would give all covid details of the country and even had a flag displayed in the pop up.
3. Search functionality - Instead of searching to get a state and get all its information, I had a drop down that has all countries and once one is selected, I have Information boxes that get populated with information of that state.
