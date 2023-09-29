# My first Express project

This project is a question and answer website developed using Node.js, Express framework, and MongoDB database. Users can register, log in, ask questions, and answer questions asked by others. The website allows users to mark one answer as accepted for their questions. 

## Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/download-center?jmp=nav#community) or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

## Installation

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/SinisaV/My-first-Express-project.git
   ```

2. Install dependencies using npm.
   ```bash
   npm install
   ```

3. Run the application.
   ```bash
   npm run start
   ```

## Features

- **User Authentication:** Users can register, log in, and log out.
- **Ask Questions:** Registered users can ask questions with titles, descriptions, and optional tags.
- **Answer Questions:** Users can answer questions asked by other users.
- **Accept Answers:** Question authors can mark one answer as accepted for their questions.
- **View Questions:** Users can view a list of questions, sorted by the date they were asked.
- **Delete Questions/Answers:** Users can delete their questions or answers.

## Technologies Used

- **Node.js:** JavaScript runtime environment.
- **Express:** Web application framework for Node.js.
- **MongoDB:** NoSQL database for storing questions, answers, and user information.
- **Bootstrap:** Front-end framework for better visualization.
- **Mongoose:** MongoDB object modeling for Node.js.
  
## Usage

1. Make sure MongoDB is running. If not, start your MongoDB server.

2. Visit `http://localhost:3000` in your web browser to access the application.

3. Register a new account, log in, and start asking and answering questions.

## Note

- The project includes a `config.js` file where you should put your MongoDB connection string.
- This project does not include the `node_modules` folder. Make sure to run `npm install` after cloning the repository to install all dependencies.
