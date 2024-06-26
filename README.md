# I-m-Bored
Random Task Generator
Welcome to the Random Task Generator! This project leverages API knowledge to retrieve data and display random tasks you can do based on filters or randomly.

Table of Contents
Description
Features
Technologies Used
Installation
Usage
API Reference
Contributing
License
Description
This project retrieves data using an API and shows random tasks you can do based on filters or randomly. The main goal is to provide users with quick and easy access to a variety of tasks they can undertake, offering flexibility through filtering options.

Features
Retrieve random tasks from an external API.
Filter tasks based on user preferences.
Simple and intuitive user interface.
Real-time updates and task retrieval.
Technologies Used
Axios: For making HTTP requests to the API.
EJS: Embedded JavaScript templates for generating HTML markup.
Nodemon: Utility that monitors for any changes in your source and automatically restarts your server.
JavaScript: Core programming language used for both client-side and server-side scripting.
Appbrewery API: External API used for retrieving task data.
Installation
To set up the project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/random-task-generator.git
cd random-task-generator
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start
Nodemon will monitor for any changes and automatically restart the server.

Usage
Open your browser and navigate to http://localhost:3000.
View random tasks or use filters to narrow down the task suggestions.
API Reference
The project uses the Appbrewery API to fetch random tasks. The following endpoint is used:

GET /tasks/random: Retrieves a random task.
GET /tasks?filter=value: Retrieves tasks based on the specified filter.
For more details on the API, please refer to the Appbrewery API documentation.

Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch:
bash
Copy code
git checkout -b feature/your-feature-name
Make your changes.
Commit your changes:
bash
Copy code
git commit -m 'Add some feature'
Push to the branch:
bash
Copy code
git push origin feature/your-feature-name
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
