# CS465

Architecture

The Angular project structure is vastly different from that of the Express HTML customer-facing page with the main difference being the functionality that each piece provides to the application as the Express HTML is used for more of the backend side of the application while the Angular project structure is used for the front-end, user-facing part of the application. Additionally, the Angular project structure is primarily component based with each component having a separate folder whereas the Express HTML structure follows a server-side MVC pattern with separate HTML files that follow routes and controllers. The backend of the project used a NoSQL MongoDB database because of how simple and easy it was to change the functionality, scaling, and overall view of the app.

Functionality

JSON is a specification for how to format data and can be used with a variety of programming languages, specifically JavaScript, which uses JSON to define objects. The frontend and backend are tied together through the use of RESTful APIs and JSON. There were multiple features that were refactored into components for the SPA toensure reusability and functionality. For instance, the navigation bar, trip cards, trip listings, edit and add trip functionalities were all refactored into their own components to allow us to reuse different parts when needed and ensure the design of the components flow well with each other.

Testing

The process of testing to make sure the SPA is working with the API and HTTP methods of GET, PUT, POST, and DELETE data in the database starts with Postman to ensure the different variables of the trips are able to be viewed, added, updated, and deleted and then moves to the application where confirmation can be made on whether or not the data is available and/or updated. The API endpoints allow the client to communicate with the server using these HTTP methods. In this full stack application security consisted of authenticating a user by having them log in with a unique username and password, and then giving them a valid JWT so they could access the endpoints.

Reflection

This course has helped me in reaching my professional goals and helped me develop more skills by allowing me to complete hands-on work with NoSQL databases, Postman and MongoDB. Additionally, this course has helped me understand the difference between a static and dynamic website, as well as what goes into creating both.
