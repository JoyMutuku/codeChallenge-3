# codeChallenge-3
Flatdango Movie Ticket Booking Application

By Joy Mwende Mutuku

Flatdango is a web application that allows users to purchase movie tickets from the Flatiron Movie Theater. This project aims to provide an interactive and user-friendly interface for browsing available movies, checking showtimes, and buying tickets.

Features
Display movie details: Upon loading the page, the application fetches data from a local server and displays the details of the first movie. The details include the movie poster, title, runtime, showtime, and the number of available tickets.
Movie menu: A menu on the left side of the page shows all available movies. Clicking on a movie in the menu updates the displayed movie's details with the selected movie's information.
Ticket purchase: Users can buy movie tickets by clicking the "Buy Ticket" button. The number of available tickets dynamically updates on the frontend, and users cannot purchase tickets if the showing is sold out.
Technologies Used
HTML5
CSS3
JavaScript
JSON DB Server (local server)
Setup and Installation
Clone the GitHub repository: https://github.com/JoyMutuku/codeChallenge-3
Navigate to the project directory: cd flatdango
Open the index.html file in a web browser.
JSON DB Server
This application fetches movie data from a local server running JSON DB Server. The server provides movie information through a REST API. The server can be started by running the following command:

bash
Copy code
json-server --watch db.json
Project Structure
index.html: The main HTML file that contains the structure of the web application.
styles.css: The CSS file for styling the application.
script.js: The JavaScript file for implementing the application logic and interaction with the server.
Contributions
Contributions to the project are welcome! If you find any issues or have suggestions for improvements, please open an issue in the GitHub repository or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
This project is part of a school assessment for [insert school name].
Movie data provided by [Flatiron Movie Theater].
