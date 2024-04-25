# Capital Quiz

Capital Quiz is a simple web application built with Node.js, Express.js, PostgreSQL, and EJS. It quizzes users on their knowledge of country capitals.

## Features

- Quizzes users on country capitals.
- Keeps track of the user's total score.
- Uses a PostgreSQL database to store quiz data.

## Setup

1. **Clone the Repository:**
```bash
  https://github.com/knull23/World-Capital-Quiz.git
```
2. **Install Dependencies:**
```bash
   install npm init -y
   install express ejs axios
   node index.js
```
3. **Set up PostgreSQL:**

- Make sure you have PostgreSQL installed and running on your machine.
- Create a database named `world`.
- Create a table named `capitals` with columns `country` and `capital`, and populate it with quiz data.

4. **Configure Database Connection:**

- Open `index.js` and modify the database connection parameters (`user`, `host`, `database`, `password`, `port`) in the `db` object to match your PostgreSQL configuration.

5. **Run the Application:**
```bash
npm start
```
6. **Access the Application:**

Open your web browser and go to `http://localhost:3000` to access the application.

## Usage

- The homepage will display a random country and prompt the user to enter its capital.
- After submitting an answer, the application will inform the user if the answer was correct and display the next question.
- The user's total score will be displayed at the bottom of the page.

## Contributions
Contributions are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.
