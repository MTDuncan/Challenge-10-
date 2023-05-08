Object-Oriented Programming Challenge: Team Profile Generator
This is a Node.js command-line application that takes in information about employees on a software engineering team and generates an HTML webpage that displays summaries for each person. The application utilizes the Inquirer package to prompt the user for input and requires version 8.2.4. To install Inquirer, use the following command in your project folder: npm i inquirer@8.2.4.

Installation
To install the dependencies for this application, run the following command in your terminal:

Copy code
npm install
Usage
To start the application, run the following command in your terminal:

Copy code
node index.js
You will be prompted to enter the team manager's name, employee ID, email address, and office number. Once you've entered the manager's information, you will be presented with a menu with the option to add an engineer or an intern, or to finish building your team. When you select the engineer option, you will be prompted to enter the engineer's name, ID, email, and GitHub username. When you select the intern option, you will be prompted to enter the intern's name, ID, email, and school.

When you decide to finish building your team, the application will generate an HTML file that displays a nicely formatted team roster based on the information you provided. If you click on an email address in the HTML, your default email program will open and populate the TO field of the email with the address. If you click on a GitHub username, the GitHub profile will open in a new tab.

Testing
This application includes unit tests for each part of the code using Jest, to ensure it passes all of them. To run the tests, use the following command in your terminal:

arduino
Copy code
npm run test
Walkthrough Video
Submited with work.

Questions
If you have any questions or feedback, please feel free to contact me.
