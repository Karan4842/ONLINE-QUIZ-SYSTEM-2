# ONLINE QUIZ SYSTEM
Features
Login Screen: Allows users to enter their name to start the quiz.
Instructions: Displays rules and guidelines before starting the quiz.
Quiz Interface: Presents multiple-choice questions and tracks the user's answers.
Result Calculation: Scores the user based on correct answers.
User-Friendly GUI: A clean and interactive interface for a seamless experience.
Prerequisites
Java Development Kit (JDK): Make sure JDK 8 or above is installed on your system.
IDE: Recommended to use an IDE like IntelliJ IDEA, Eclipse, or NetBeans for easy project management. Alternatively, you can use the command line to compile and run.
Project Structure
bash
Copy code
quiz.application
├── Login.java          # Handles user login interface
├── Rules.java          # Displays rules before starting the quiz
├── Quiz.java           # Main quiz interface with questions
├── Result.java         # Shows the final result and score
├── icons               # Contains images used in the UI
    └── login.jpeg      # Background image for login screen
How to Run
Compile the Project:

Navigate to the root folder containing quiz/application directory.
Run the following command to compile all Java files:
bash
Copy code
javac quiz/application/*.java
Run the Application:

Start the application by running the Login class:
bash
Copy code
java quiz.application.Login
Usage
Launch the program, and a login screen will appear.
Enter your name and click the "Rules" button to view quiz instructions.
Click "Start Quiz" to begin answering the questions.
At the end of the quiz, your score will be displayed.
Customization
Adding Questions: Edit the Quiz.java class to add or modify questions.
Changing Rules: Update the Rules.java class to adjust quiz guidelines.
UI Customization: Modify the JFrame components to customize fonts, colors, and layout.
Future Enhancements
Add a timer for each question.
Implement a database to store user scores.
Add more question categories and randomize question order.
License
This project is for educational purposes and is not intended for commercial use.
