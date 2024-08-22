
---
# Quiz App

## Introduction

Welcome to the Quiz App! This is a simple web-based quiz application designed to test your knowledge on various topics. Built using HTML, CSS, and JavaScript, the app provides a clean and engaging interface for users to answer questions and receive immediate feedback on their performance.

Visit: **https://nehra-quiz-app.netlify.app/**

## Features

- **Interactive Quiz**: Answer multiple-choice questions and get instant feedback.
- **Score Tracking**: Keep track of your score as you progress through the quiz.
- **Customizable Questions**: Easily change the questions to suit your needs.

## Usage

1. Clone or download the repository.
2. Open the `index.html` file in your browser.
3. Start the quiz and answer the questions.

## Customizing Questions

To customize the quiz questions:
1. Open the `script.js` file located in the project directory.
2. Locate the `questions` array of objects.
3. Modify the existing questions or add new ones according to your preferences.

Example:

```javascript
const questions =[
    {
        question: "Your custom question here?",
        answers:[
            {text: "Option 1", correct: false},
            {text: "Option 2", correct: true},  //correct option
            {text: "Option 3", correct: false},
            {text: "Option 4", correct: false},

        ]
   },
    // Add more questions here
];
```

## Screenshots
![image](https://github.com/user-attachments/assets/50e35178-ed3e-48f1-a71b-cad7c6478f85)

