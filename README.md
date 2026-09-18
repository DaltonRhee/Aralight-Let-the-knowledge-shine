# Aralight: Let the knowledge shine

## Group Number and Members

Group Number: 6

Members:
- Consulta, Justin Mark
- Dapilaga, Paul Yushua
- Montoya, Dalton Rhee

## Project Description

Aralight is a learning-based game prototype designed to make studying more enjoyable and engaging. The game combines quiz gameplay with subject-based progression, allowing players to learn while they play. The prototype focuses on interactive educational experiences in multiple subjects such as Math, English, Filipino, and Science.

The goal of the game is to let players enjoy learning through levels, score tracking, and subject-based challenges while encouraging progress and repetition in a fun format.

## Tools and Technologies Used

- Unity 6
- C#
- TextMeshPro
- Firebase Authentication
- Firebase Realtime Database
- Unity UI System
- Visual Studio / VS Code
- JSON-based quiz data

## Database or Storage Option Used

This project uses Firebase Realtime Database for storing quiz results and user-related data such as:
- player scores
- subject results
- level progress
- teacher/student role information

Firebase Authentication is also used for logging in users and verifying user identity.

## How to Run the Prototype

1. Open the project in Unity Hub.
2. Open the Aralight Unity project folder.
3. Make sure the correct Unity version is installed and selected.
4. Open the project scene for the login or main menu flow.
5. Press Play in Unity Editor to run the prototype.
6. Log in as a student or teacher using the configured Firebase account.
7. Select a subject and level to begin the quiz.

Notes:
- Firebase must be configured in Unity before running the project.
- The Firebase project must already be connected to the Unity project and database rules must be published.
- If testing a teacher dashboard, ensure the teacher account has the correct role in Firebase.

## What Data Is Saved and Retrieved

The prototype saves and retrieves the following information:

### Saved Data
- user ID
- player name
- subject selected
- level reached or completed
- score
- correct answers
- wrong answers
- stars earned
- total questions
- completion status
- timestamp

### Retrieved Data
- current user login status
- user role (student or teacher)
- subject progress
- level statistics
- leaderboard data
- teacher dashboard analytics by subject

This data is used to update the leaderboard, unlock the next level, and show teacher analytics for each subject.

## Known Limitations or Unfinished Parts

- Some Firebase rules may still need refinement depending on project requirements.
- Teacher dashboard display is still focused on basic analytics and can be improved visually.
- Game content may still need more subjects, levels, or polishing.
- Some UI elements may require further tuning for a final production-ready look.
- The project is still a prototype and may not yet include full content balancing or advanced game systems.

## References or Tutorials Used

This project was built using knowledge from the following general sources and learning areas:

- Unity official documentation
- Firebase Unity integration documentation
- TextMeshPro UI tutorials
- Unity C# scripting references
- Firebase Realtime Database setup guides
- Unity scene navigation and UI interaction tutorials

If specific external tutorials were used during development, they were applied as support for Firebase setup, Unity UI design, and quiz/game flow implementation.

---

## Summary

Aralight is an educational game prototype that combines quiz-based learning with interactive progression and Firebase-powered data tracking. The project aims to make learning more engaging while allowing teachers to monitor student performance through a subject dashboard.
