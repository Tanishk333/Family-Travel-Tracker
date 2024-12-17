# Family Travel Tracker
Description
The Family Travel Tracker is a web-based application designed to keep track of countries visited by each family member, providing a dynamic and interactive map visualization. The project utilizes JavaScript, CSS, and PostgreSQL for front-end interactivity and backend database management. The aim of the project is to create a user-friendly platform where families can visually document and manage their travels in a collaborative manner.

The application allows users to add multiple family members, assign them custom colors, and log the countries they visit. Each user is stored in a PostgreSQL database with a unique ID, name, and color preference. When a country is logged as "visited" by a specific family member, its corresponding color on the map dynamically updates based on that user's assigned color. This interactive feature provides a clear, visual representation of each family member's travel history, fostering a sense of connection and achievement.

The backend is built using Node.js with Express.js to manage server operations and handle user requests. User and travel data are retrieved and updated in real-time using SQL queries. The visited countries are stored as records linking the user ID and the respective country code. Users can easily add new family members and log their travel activity using a user-friendly form, which integrates smoothly with the backend for seamless functionality.

The front end, powered by JavaScript and styled with responsive CSS, dynamically renders the map with updated country colors using DOM manipulation techniques. This ensures that users get instant feedback as travel information is added or updated. A visually appealing and interactive UI makes the system both functional and engaging on desktop and mobile devices.

The project effectively combines data storage, dynamic UI updates, and real-time interactivity to deliver a collaborative experience. It also showcases technical skills in full-stack development, including database design, server implementation, and client-side scripting.

Interactive Map Visualization: Developed a dynamic feature to color countries on a map based on visits by specific family members, ensuring a visually engaging representation of travel history.
Robust Data Management: Implemented a PostgreSQL database to efficiently store and retrieve user information and visited countries, integrating it with a Node.js-powered backend for real-time updates.
This project highlights practical experience in full-stack web development, covering database design, server-side logic, and dynamic front-end interactivity to create an engaging, family-oriented tool.
