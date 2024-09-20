# Getting Started with Create Nasa React App

# NASA Data Explorer
**Project Overview**

> This project is a web application built using the React.js framework, styled with Tailwind CSS, and designed to provide users with information from the NASA API. The application fetches data from NASA's Astronomy Picture of the Day (APOD) API endpoint, offering users access to daily images and detailed descriptions of astronomical events and phenomena.
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### Access NASA Api 

**To access the NASA API and integrate it into your project, follow these steps:**


- Step 1: Get an API Key
Visit the NASA API Website: Go to https://api.nasa.gov/.
Request an API Key:
Scroll down to the "Get Started" section.
Fill in the required information such as your name and email.
Agree to the terms and submit the form.
You will receive an API key via email, which you can use to access the NASA APIs.

- Step 2: Choose the API Endpoint
NASA provides multiple endpoints, such as:

Astronomy Picture of the Day (APOD): Provides a daily image or video with a description.
Mars Rover Photos: Retrieves images captured by Mars rovers.
NeoWs (Near Earth Object Web Service): For information about asteroids and other near-Earth objects.
For this example, we'll use the APOD endpoint:

Endpoint URL: https://api.nasa.gov/planetary/apod


- Step 3: Make an API Request

1. Construct the API Request URL: Include your API key as a query parameter in the URL. For example:
`https://api.nasa.gov/planetary/apod?api_key=YOUR_API_KEY`

2. Optional Parameters:
date: (Optional) The date of the APOD in YYYY-MM-DD format.
hd: (Optional) If set to true, return the URL of the high-definition image.


- Step 4: Integrate with Your React Application
1. Create a .env File: Store your API key in an environment variable to keep it secure.
_REACT_APP_NASA_API_KEY=your_api_key_here_
2. Fetch Data in Your React Component: Use the fetch API or any other HTTP client to get data from the API


- Step 5: Run Your Application
Install Dependencies: Ensure your project dependencies are installed
`npm install`
Start the React Application:
`npm start`


- Step 6: Deployment Considerations
Hide Your API Key: Never expose your API key in the client-side code or GitHub repository. Use environment variables or a backend server to handle the API requests securely


This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
