# I-m-Bored
# Random Task Generator

Welcome to the Random Task Generator! This project leverages API knowledge to retrieve data and display random tasks you can do based on filters or randomly. 

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)

## Description

This project retrieves data using an API and shows random tasks you can do based on filters or randomly. The main goal is to provide users with quick and easy access to a variety of tasks they can undertake, offering flexibility through filtering options.

## Features

- Retrieve random tasks from an external API.
- Filter tasks based on user preferences.
- Simple and intuitive user interface.
- Real-time updates and task retrieval.

## Technologies Used

- **Axios**: For making HTTP requests to the API.
- **EJS**: Embedded JavaScript templates for generating HTML markup.
- **Nodemon**: Utility that monitors for any changes in your source and automatically restarts your server.
- **JavaScript**: Core programming language used for both client-side and server-side scripting.
- **Appbrewery API**: External API used for retrieving task data.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone hhttps://github.com/aman090304/I-m-Bored
   cd random-I-m-Bored

2. **Install dependencies:**
   ```bash
   npm install
3.**Start the deployment server:**
   ```bash
   npx nodemon index.js

```
## Usage

1. **Open your browser** and navigate to `http://localhost:3000`.
2. **View random tasks** or use filters to narrow down the task suggestions.

## API Reference

The project uses the Appbrewery API to fetch random tasks. The following endpoint is used:

- **GET /tasks/random**: Retrieves a random task.
- **GET /tasks?filter=value**: Retrieves tasks based on the specified filter.

For more details on the API, please refer to the [Appbrewery API documentation](https://www.appbrewery.co/documentation).

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/your-feature-name

3. **Make your changes** to the codebase.


4. **Stage your changes** for commit:
   ```bash
   git add .
   git commit -m 'Add some feature'

5. **Push your changes:**
   ```bash
   git push origin feature/your-feature-name

**Create a pull request**
Open a pull request on GitHub:
-Go to your repository on GitHub.
-Switch to the branch where you made your changes.
-Click on "New pull request."
-Provide a title and description for your pull request.
-Click on "Create pull request" to open it for review.

