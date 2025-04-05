# CodeMaster
Gen AI interactive coding game
College-GNIOT(132)
Group Name-Silicon Mavericks
Group Member
Navya Mishra(B.Tech-AIML(3rd Year)
Suhani Kumari((B.Tech-AIML(3rd Year)
Vaibhavi(B.Tech-AIML(3rd Year)

This Quiz Application is a web-based platform that allows users to take quizzes in various languages and levels. Users can log in, select a language and level, answer questions, and view their results. The application is built using HTML, CSS, and JavaScript.

Features:--
User authentication (login/logout)
Language selection
Level selection
Quiz functionality with multiple-choice questions
Timer for each quiz
Results display with performance feedback
Ability to unlock new levels based on performance

Technologies Used:--
HTML: Structure of the web application
CSS: Styling and layout
JavaScript: Functionality and interactivity
Local Storage: Storing user progress and unlocked levels

Usage:--
Login: Enter your username to start.
Select Language: Choose a language from the available options.
Select Level: Choose a level to begin the quiz.
Answer Questions: Click on the options to select your answer.
Submit Quiz: After answering all questions, submit to see your results.
Restart Quiz: Option to restart or move to the next level if unlocked.

Code Explanation:--
State Management
The application maintains a state object to track user information, selected language, level, questions, and answers.

DOM Elements:--
The application uses a set of DOM elements to manage the user interface, including modals, quiz sections, and result displays.

Functions:--
showLoading/hideLoading: Manage loading spinner visibility.
handleLogin/handleLogout: Manage user login and logout.
setupLanguageSelection/setupLevelSelection: Manage language and level selection.
fetchQuestions: Fetch quiz questions from the server.
renderQuestion: Display the current question and options.
submitQuiz: Calculate and display the user's score.
