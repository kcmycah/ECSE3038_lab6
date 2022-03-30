# ECSE3038_lab6
## Aim

This lab is meant to get students more accustomed to the technologies used in designing and implementing an HTML frontend application and RESTful API server.

## Requirements

Now that the backend server has been fully implemented, now all that's left is to to design and implement a user friendly GUI (graphical user interface) for the tank management application.

This frontend app should be used to allow a user to interface with the kind of data that the backend server was built to handle. 

**GET /data**

When your app loads, **it** should make a GET request to the server to retrieve the list of tank objects saved in the database. Use the retrieved tank objects to dynamically create your tank cards to be displayed on screen.

**POST /data**

The app should provide a user with a simple form that accepts the various attributes of of a tank object. 

The form should accept the following:

- Tank location description
- Latitude
- Longitude
- Percentage full

The data from your form should be used to create the JSON body of a POST request. The POST request should be sent to your backend server and used to create a new tank object that should be stored in your database.

**HTML and CSS**

The tank objects pulled from the server should be used to populate cards or blocks. These cards should be designed to display all the attributes of each tank object.

The HTML layout of a tank object can as simple or as complex a design as desired, as long as it makes sense. 

Add a suitable header to the top of you web app to display the name of the system. The name of the application is up to you.

Use CSS to style your tank objects, the "new tank" form, and the page header.

Your HTML, CSS and JavaScript code must be written in their own separate file.

- index.html
- style.css
- script.js

Your web-component related code should be located in a folder called TankCard with the web-component javascript code called tank-card.js and the css file called tank-card.css.

Any other media (eg. images, etc.) that need to be included should be put stored in a folder called `assets`.
