# React Quiz

## Overview

React Quiz is a sandbox React project built to explore reusable quiz and assessment features for a much larger educational LMS platform currently in development. The long-term goal of the platform is to teach students coding and technology concepts through interactive academic content and historical learning modules.

This project focuses specifically on building a modular quiz system using React state management patterns, reusable UI components, timed assessments, and scalable architecture that can later be integrated into a larger Next.js application.

## Goals of the Project

This project was created to practice and better understand:

- React component architecture
- `useReducer` state management
- Refactoring reducer logic into the Context API
- Building reusable quiz components
- Conditional rendering patterns
- Timers and score tracking
- Managing global application state with custom hooks
- Preparing React applications for deployment

The original version of the application managed all quiz logic directly inside the `App` component using `useReducer`. The project was later refactored to move quiz state into a dedicated `QuizContext` provider with a custom `useQuiz()` hook to create a cleaner and more scalable architecture.

## Features

- Timed quiz functionality
- Dynamic question rendering
- Score tracking
- High score tracking
- Progress indicator
- Restart quiz functionality
- Global state management using Context API
- Modular reusable React components
- Static JSON-based question data
- Responsive UI
- Deployed to Vercel

## Demo

- **Live App**: https://react-quiz-swart-eight.vercel.app/

## Tech Stack

- React
- Context API
- useReducer
- JavaScript (ES6+)
- CSS
- Vercel

## Architecture Notes

The current version uses static JSON data imported directly into the React application. Earlier versions used `json-server` and API fetching during development, but the project was later simplified for deployment and portability.

This project is part of a broader collection of educational UI experiments, including modal-based historical player cards and interactive learning dashboards, which will eventually combine into a larger LMS platform built with Next.js.

The goal of these smaller projects is to prototype reusable educational components before integrating them into the larger production platform.

## Future Plans

- Convert the quiz system into a reusable assessment component
- Add category-based quizzes
- Persist user progress and scores
- Add animations and transitions
- Integrate quizzes into larger educational learning modules
- Connect quizzes with historical and coding lesson content
- Migrate features into a larger production LMS platform

## Local Development

Clone the repository:

```bash
git clone https://github.com/wesnimmo/react-quiz.git
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

## Author

Built by Wesley Nimmo as part of an ongoing educational LMS and front-end development initiative.