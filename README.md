# Interactive-Quiz-App
The Beginner SQL Quiz App is a fully responsive and interactive quiz built using HTML, CSS, and JavaScript. It features 25 multiple-choice questions designed to test and reinforce foundational SQL concepts. Ideal for beginners preparing for interviews, exams, or brushing up on SQL basics.




HTML 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Beginner SQL Quiz</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="quiz-container">
    <h1>Beginner SQL Quiz</h1>

    <div class="progress-bar">
      <div id="progress-fill"></div>
    </div>

    <div id="timer">Time left: <span id="time">30</span>s</div>

    <div id="question">Question text will appear here</div>

    <ul id="options"></ul>

    <button id="next-btn">Next</button>

    <div id="result" class="hidden">
      <h2>Your Score: <span id="score"></span> / 25</h2>
      <button onclick="location.reload()">Restart Quiz</button>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
