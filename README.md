
🎓 Quiz-App 📝
This is a console-based Quiz Application implemented in Python. The application allows users to register, log in, take quizzes on various topics, and view their scores. It supports multiple topics, each with its own set of multiple-choice questions.

✨ Features
👤 User Registration:

Users can create a new account with a unique username and password.
Passwords are securely handled using the getpass module to hide input.
🔒 User Login:

Existing users can log in using their credentials.
Only valid credentials will allow access to the quiz features.
📚 Take Quiz:

Users can choose from three topics:
📂 DBMS
⚙️ DSA
🐍 Python
Each topic has a predefined set of multiple-choice questions.
Correct answers are scored, and incorrect answers display the correct option.
📊 View Score:

Users can view their most recent quiz score for the topic they attempted.
🚪 Exit:

Users can exit the application at any time.
🛠 Code Structure
Registration:
Validates if the username already exists before creating a new user.
Login:
Checks user credentials and provides access to quiz functionality upon successful login.
Quiz:
Asks a series of multiple-choice questions for the selected topic.
Tracks the user's score for correct answers.
Score Display:
Displays the user's most recent quiz score.
🚀 Usage
Run the App: Execute the Python script to start the application:

bash
Copy code
python quiz-app.py
Options:

Choose from the main menu options: 1️⃣ Register to create a new user account.
2️⃣ Login to access the quiz.
3️⃣ Exit to close the application.
Quiz Flow:

After logging in, choose a topic to take a quiz.
Answer the multiple-choice questions by typing the option letter (A, B, C, D).
At the end of the quiz, your score will be displayed.
View Results:

Use the "Show Result" option after logging in to see your last quiz score.
📜 Topics and Questions
📂 DBMS: Questions related to database concepts.
⚙️ DSA: Questions related to data structures and algorithms.
🐍 Python: Questions related to Python programming basics.
📌 Example Output
plaintext
Copy code
1. Register
2. Login
3. Exit
Choose an option: 2
Enter username: John
Enter password:
Welcome, John!

1. Take Quiz
2. Show Result
3. Logout
Choose an option: 1

Choose a topic for quiz:
1. DBMS
2. DSA
3. Python
Enter the number of your chosen topic: 3

--- Python Quiz ---
What is the output of 'print(2 ** 3)'?
A) 5
B) 6
C) 8
D) 9
Your answer (A, B, C, D): C
Correct!

...

You scored 4/5 in Python quiz.
