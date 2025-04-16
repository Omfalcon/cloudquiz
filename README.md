Sure! Here's a sample README file update for your project that includes the links you provided:

---

# CloudQuiz - Quiz Application

CloudQuiz is an interactive quiz application built using Firebase and web technologies (HTML, CSS, JavaScript). It allows users to create quizzes, take them, and view real-time leaderboards.

### Features:
- **Create Quiz**: Users can create custom quizzes with multiple choice questions and options.
- **Play Quiz**: Players can participate in quizzes, answer questions, and see their scores in real-time.
- **Leaderboard**: View live leaderboards based on quiz performance.

### Live Demo:
- **Create Quiz**: [Create Quiz - CloudQuiz](https://quzizz-5caac.web.app)
- **Leaderboard**: [Leaderboard - CloudQuiz](https://quzizz-5caac.web.app/leaderborad.html)

### Tech Stack:
- **Frontend**: HTML, CSS, JavaScript (Vanilla)
- **Backend**: Firebase Firestore (for storing quiz data and responses)
- **Hosting**: Firebase Hosting

---

### Instructions to Run Locally:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cloudquiz.git
    ```

2. Install Firebase tools (if you haven't already):
    ```bash
    npm install -g firebase-tools
    ```

3. Login to Firebase:
    ```bash
    firebase login
    ```

4. Deploy to Firebase (after setting up your Firebase project):
    ```bash
    firebase deploy --only hosting
    ```

---

### Firebase Setup:
1. If you're setting up Firebase for the first time, create a Firebase project and get the Firebase credentials (`firebaseConfig`).
2. Initialize Firebase in your app with the credentials from the Firebase console.

---

This should provide a clear overview of your project and how users can interact with it, along with links to the live demo.
