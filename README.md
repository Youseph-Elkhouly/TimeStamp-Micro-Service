# TimeStamp-Micro-Service

Link: https://alabaster-catnip-nylon.glitch.me

This is a full stack JavaScript app

🛠 Features
Accepts a date parameter (either a Unix timestamp or a date string)

Returns a JSON response with:

unix: timestamp in milliseconds

utc: UTC string formatted date

Returns the current timestamp if no date is provided

Gracefully handles invalid dates with { error: "Invalid Date" }

📦 Technologies Used
Node.js

Express.js

JavaScript (ES6)

Glitch (for hosting and live editing)

🧪 Example API Usage

GET /api/2015-12-25
→ { "unix": 1451001600000, "utc": "Fri, 25 Dec 2015 00:00:00 GMT" }

GET /api/1451001600000
→ { "unix": 1451001600000, "utc": "Fri, 25 Dec 2015 00:00:00 GMT" }

GET /api/
→ { "unix": 1698342451983, "utc": "Tue, 26 Oct 2023 22:47:31 GMT" }

GET /api/invalid-date
→ { "error": "Invalid Date" }
