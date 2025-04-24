# Timestamp Microservice

This is a full stack JavaScript microservice that parses dates and timestamps into a clean JSON API. It's part of my journey through the freeCodeCamp APIs and Microservices Certification, and a solid foundation for learning RESTful API development.

link to website: https://alabaster-catnip-nylon.glitch.me

Features
Accepts a valid date string or Unix timestamp via the API

Returns a formatted JSON object with both:

unix: milliseconds since the epoch

utc: UTC-formatted date string

Automatically returns the current timestamp when no date is provided

Returns { error: "Invalid Date" } for invalid inputs

Tech Stack
Node.js

Express.js

Glitch (for live deployment)

JavaScript (ES6)
