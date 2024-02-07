# Test Your Knowledge

Test Your Knowledge is a straightforward application built with React.js, designed to assess users' understanding of the articles they read about GitHub Pages. Additionally, it is responsive, ensuring a seamless user experience across various devices.

## 🧵 Contents

-   [Technologies](https://github.com/Deerah1234/TechCompendium/blob/main/2024-01-15-Mastering-GitHub-Pages-Deploy-React-with-Vite/code/README.md#%EF%B8%8F-technologies)
-   [How can it be improved?](https://github.com/Deerah1234/TechCompendium/blob/main/2024-01-15-Mastering-GitHub-Pages-Deploy-React-with-Vite/code/README.md#-how-can-it-be-improved-1)
-   [Running the Project](https://github.com/Deerah1234/TechCompendium/blob/main/2024-01-15-Mastering-GitHub-Pages-Deploy-React-with-Vite/code/README.md#%EF%B8%8F-running-the-project)

## 🛠️ Technologies

-   `Vite`
-   `React.js`
-   `TailwindCss`

## 🚀 How can it be improved?

I initiated the project by bootstrapping a Vite app. Following that, I installed Tailwind CSS.

The first rendering involved creating a welcome page, designed to be displayed only once. This was achieved by saving a key in the local storage. The welcome page includes a button that, when clicked, directs users to the quiz component.

Within the quiz component, I implemented the rendering of a timer, quiz questions, and options. The data for these components is sourced from a quizData object. Utilizing the map function, I dynamically generated the options. The quiz component also includes navigation buttons for both previous and next questions.

Subsequently, I created the completion component. This component displays the user's score, highlights the correct answers, and provides options to share the results on Twitter, reset the quiz, and offer feedback.

## 🌱 How can it be improved?

-   Implement a feature to display the time spent on the quiz.
-   Enhance user experience by adding more themes such as dark mode, light mode, and additional options.
-   Refine the overall user interface for a more polished and intuitive design.

## ▶️ Running the Project

To run the project in your local environment, follow these steps:

1. Clone the repository to your local machine.
2. Run `npm install` or `yarn` in the project directory to install the required dependencies.
3. Run `npm run dev` or `yarn dev` to get the project started.
4. Open http://localhost:5173/testyrkno (or the address shown in your console) in your web browser to view the app.
