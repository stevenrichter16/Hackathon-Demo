# ClearDoc, an AI-powered doctor's assistant for simplifying medical terminology

## Demo: https://youtu.be/U7bLF-driH0?t=298 at timestamp 4:58

### Credits
Front-end (React.js) / Back-end (Flask): **Steven Richter** | stevenrichter16@gmail.com

Styling (CSS/SCSS): **Tim Uster** | timuster@live.com

GPT-3 Prompt Engineering: **Alan Majer** | alanmajer@hotmail.com ||
                          **Matthew Donaruma** | matt@mdonaruma.com

### What/Why?
The motivation for this application came from recognizing the dense and confusing nature of clinical notes and medical terminology With the use of GPT-3, a deep learning model developed by OpenAI, my OpenAI/NextGrid hackathon team surmized the concept of an application that translates medical lingo into simple English. This application/assistant provides patients a better overall clinical experience.  

### Development Process

Over the course of 8 hours I created the front-end and back-end from scratch, only having moderate knowledge of React.js, and minimal knowledge of Flask. Through much trial and error I accomplished setting up a REST API with Flask.

The main issue I encountered in creating the API centered around the POST method. Previously I used Flask to set up a GET endpoint, but I had never developed an API a POST endpoint wherein the client could send user data to the server to have it processed, then back to the client. The need for this functionality came from the need to grab user input from the client, send it to the Python server, process it through the GPT-3 API, then send that data back to the client to be displayed. The majority of the development time spent consisted of fixing errors with the POST method. Once I succeeded in writing the POST method I realized how simple it was in hindsight.

### Conclusion

Overall this project gave me experience in full-stack web development, and sharpened my communication skills. Since this application is a demo, it is not developed to its fullest potential. In the future this application could be used by doctors and nurses across English speaking countries, and additional language options could be added. We think this AI assistant highlights the nascence of AI-powered health services, of which will revolutionize the field of medicine.  

A url for this web application will be available soon. Here is the slide deck for the presentation we gave during the hackathon: https://docs.google.com/presentation/d/1lIQbtUXYoazawjZ-VRQ_8Shp3e8G37gkbUy-jFxrqlI/edit?usp=sharing

Disclaimer: If you run the project from the source files it will not work since it requires me to reveal my GPT-3 API key. I am working to fix that, a demo of this app is located at the top of this document.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
