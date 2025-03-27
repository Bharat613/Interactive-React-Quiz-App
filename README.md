# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# Interactive React Quiz App

## Description
This is a dynamic and interactive quiz application built with React. It allows users to answer multiple-choice questions, keeps track of their scores, and provides instant feedback on their answers.

## Features
- Multiple-choice questions
- Score tracking
- Instant feedback with correct and incorrect answers
- Ability to reset and restart the quiz
- Responsive design for mobile and desktop

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Bharat613/Interactive-React-Quiz-App.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Interactive-React-Quiz-App
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Usage
1. Start the development server:
   ```sh
   npm start
   ```
2. Open the app in your browser:
   ```
   http://localhost:3000
   ```

## Deployment
To deploy the app on GitHub Pages:
1. Install the GitHub Pages package:
   ```sh
   npm install gh-pages --save-dev
   ```
2. Add the following scripts in `package.json`:
   ```json
   "homepage": "https://your-username.github.io/Interactive-React-Quiz-App",
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```
3. Deploy the app:
   ```sh
   npm run deploy
   ```

## Technologies Used
- React.js
- HTML
- CSS
- JavaScript

## License
This project is licensed under the MIT License.

## Author
Bharat Venkata Siva Katta

