Travlr App - Full Stack Web Application

Overview

Travlr is a full stack web application designed to showcase travel destinations while enabling admin users to securely manage trip data. Built with Angular on the frontend and Express.js with MongoDB on the backend, the project demonstrates modern single-page application (SPA) development, API integration, and secure user authentication.

⸻

Architecture

The frontend was built using Angular, which enabled the creation of a dynamic SPA with reusable components, routing, and form handling. Unlike the backend, which used Express.js to handle HTTP requests, the Angular SPA allowed for seamless updates to the UI without full page reloads. This provided a smoother user experience and more responsive interface compared to traditional HTML and JavaScript rendering in Express-based applications.

MongoDB was chosen as the backend database because of its NoSQL structure, which pairs naturally with JavaScript-based JSON data formats. Its schema-less design made development flexible and well-suited for the evolving data needs of the app.

⸻

Functionality

JSON was a central part of the data flow in this application. It acted as the common language between the Angular frontend and Express backend. The backend served structured JSON responses from MongoDB, while the frontend consumed and displayed that data dynamically using Angular components and services.

Throughout development, I refactored components and services to be reusable and modular. This allowed me to minimize redundancy, particularly in the form-handling logic for adding and editing trips. It also made future updates easier by centralizing key functionality like API calls and data validation.

⸻

Testing

To ensure data flowed properly between the Angular frontend and Express API, I tested GET and PUT endpoints using both Postman and live interaction through the UI. I confirmed that data was retrieved from the database, displayed properly, and that updates made via forms were persisted to the backend. I also tested JWT-protected routes by simulating login and ensuring tokens were required for admin-level operations. When issues arose, such as missing model schemas or authentication failures, I debugged them by checking network requests, inspecting token headers, and validating MongoDB collection behavior.

⸻

Reflection

This course challenged me to integrate several modern web technologies into a working product. I improved my ability to structure code logically, debug issues, and understand how frontend and backend components interact. I also gained experience working with JWT authentication, MongoDB schemas, and Angular services—all of which will help me as I pursue a software development role. Building this project has strengthened my confidence as a developer and shown me how to manage complex application logic from concept to deployment.