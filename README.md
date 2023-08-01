
# Bored API Activity Suggestion Web App

This application is built using Node.js, Express, EJS, and Axios to generate random activity suggestions based on user-selected criteria. It allows users to find interesting activities to do when they are feeling bored or looking for something fun to engage in.




## Features

- Random Activity Generation: Upon loading the application or clicking the "Go" button with no specific criteria selected, the app fetches a random activity suggestion from the "Bored API" and displays it on the page.

- Activity Filter: Users can select a specific activity type (e.g., Education, Charity, Recreational, Relaxation, etc.) and the number of participants (e.g., Any number, 1, 2, 3, 4). Upon submitting the form, the app makes an API call to filter activities based on the selected criteria and displays a randomly selected matching activity.

- Error Handling: The application handles API call errors and displays appropriate error messages if there are issues with the network or no matching activities found for the selected criteria




## Installation

To run the Bored API Activity Suggestion Web App locally, follow these steps:

Clone the repository to your local machine or download the source code.

Ensure you have Node.js and npm (Node Package Manager) installed on your system.

Open a terminal or command prompt and navigate to the project directory.

Install the required dependencies by running the following command:

    npm install
    node app.js

Open your web browser and visit "http://localhost:3000" to access the application.

On the web page, you will see a form with two dropdowns: one for selecting the activity type and another for the number of participants.

To get a random activity suggestion, you can either leave the form empty or select "Random type" and "Any number of people" from the dropdowns.

If you want to filter activities, select a specific activity type and the number of participants you have in mind. Then, click the "Go" button.

The app will fetch an activity that matches the selected criteria and display it on the page. If there is an error during the API call or no matching activities found, an appropriate error message will be shown.
## Dependencies

The application relies on the following npm packages:

- express: Web framework for creating the server and handling routes.

- body-parser: Middleware for parsing form data from incoming requests.

- axios: HTTP client for making API calls.

- ejs: Templating engine for rendering dynamic HTML content.

- These dependencies are automatically installed when you run the "npm install" command.



![Screenshot 2023-08-01 103506](https://github.com/Guyaloosh/Using-JasonFilles/assets/96589390/6a3286b4-9a71-4e6f-a507-c067ed42624e)



![Screenshot 2023-08-01 103847](https://github.com/Guyaloosh/Using-JasonFilles/assets/96589390/21c7ec6f-6583-45a4-a5a9-7c7698478de4)
