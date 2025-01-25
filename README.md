# **Postgres World Capitals Quiz**

Test your knowledge of world capitals with this interactive quiz app! Dynamically pulling questions from a PostgreSQL database, this application provides a fun and educational way to learn about countries and their capitals.  

---

## **Deployed Application**

Access the live app: [Postgres World Capitals Quiz](https://postgres-world-capitals-quiz.onrender.com)  
*Note: The app may take up to 60 seconds to load, as it is hosted on Render's free tier.*

---

## **Features**

- **Dynamic Question Generation**: Fetches questions from a PostgreSQL database hosted on Neon.
- **Answer Validation**: Checks user-submitted answers against the database and provides immediate feedback.
- **Score Tracking**: Tracks the total number of correct answers in real time.
- **Interactive Webpage**: Built with EJS templates for a dynamic and engaging user experience.

---

## **Tech Stack**

- **Backend**: Node.js, Express
- **Database**: PostgreSQL (hosted on Neon)
- **Frontend**: EJS templates, HTML, CSS, JavaScript
- **Middlewares**: Body-parser
- **Deployment**: Render

---

## **How It Works**

1. **Fetching Questions**: The app pulls a list of countries and their capitals from a PostgreSQL database.
2. **Gameplay**: 
   - A random question is displayed, asking the user for the capital of a specific country.  
   - Users submit their answers via an input field.
3. **Real-Time Feedback**: 
   - Correct answers are validated against the database, and the app updates the total score.  
   - Users are shown whether their answer was correct or incorrect before proceeding to the next question.
4. **Randomization**: Questions are randomly selected to ensure no two sessions feel the same.

---

## **Future Enhancements**

- **Difficulty Levels**: Add easy, medium, and hard modes based on less common capitals.  
- **Multiplayer Mode**: Enable multiple players to compete in real time.  
- **Leaderboard**: Track high scores and showcase top players.  
- **Hints**: Provide hints for tougher questions (e.g., country location or a letter of the capital).  

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
