# SNHU-CS-465

Travlr is a RESTful web application for vacation bookings and reviews. For the client, Travlr Getaways, two userbases were used: administrators and customers. The idea of this project was to provide the customer with content-focused with a fast initial load time of the content for the end user. The administrator's for the web applicatoin needed it to be feature focued that allowed for more and more intuitive user interactions. They also needed a fast and responsive user experience opposed to quick load times the same way that the user needed.  

This project's focus was to develop a prototype of the finalized full stack web application that implemented MEAN AND MVC technologies. 


For its backend, Travlr uses Node.js and the Express framework for its web server. This web appplication uses the MongoDB noSQL database. Within the database, there is an object data model called mongoose implemented.

For the front end, Travlr uses Express.js's templating engine to dynamically generate HTML requests. Administrations The frontend that customers interact with uses a templating engine and Express.js so the server can dynamically generate HTML for requests. The administrators' frontend is an SPA delivered via Angular.
Security

The API endpoints are secured using authentication and authorization schemes that utilize JSON web tokens. When the user's credentials are authenticated, a JWT is issued to their browser's local storage. On the backend, user passwords are stored using one-way encryption and are never stored in plaintext.
The MEAN Stack

    MongoDB - NoSQL databases are known for their speed and flexibility over the more structured SQL relational databases. BSON and JSON are used to develop MongoDB code, which makes it a great candidate for a MEAN stack application which primarily uses JSON and JavaScript
   
   Express - this is a Node.js framework that makes developing Node applications much easier. Express is used in combination with Handlebars to template and dynamically render HTML pages
    
    Angular - this is the frontend framework that allows use of SPAs. With this type of architecture, clients are sent a lot of JavaScript files with the first request and can then generate all the webpages without subsequent server requests. Angular SPAs put less strain on the server and allow for a faster, more responsive user experience after the first web page loads. One downside to this approach is that it will be hard for search engines to crawl the website. Another downside to the SPA approach is that it requires a slow initial page load which may impact the user experience
   
   Node.js - this is the software platform that many modern developers use to create their web server. It is the foundation for building web applications on. JavaScript is the primary programming language used for Node and Express, making the MEAN stack easy to learn because it only requires knowledge in JavaScript

