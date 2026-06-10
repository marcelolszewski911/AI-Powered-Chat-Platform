# AI-powered chat platform
This project is a frontend application for an AI-powered chat platform, designed to provide a user-friendly interface for interacting with AI models. The application is built using React and utilizes various libraries and frameworks to enable features such as web3 modal and speech recognition.

## How it works
The application uses a React-based architecture, with a router managing client-side routing. It also utilizes the Web3Modal library to enable wallet connections and interact with the Ethereum blockchain. The app is divided into several components, including pages for home, explore, chat, and profile, which are loaded lazily using React's Suspense feature. The app also uses a context provider to manage state and props across the application.

## Tech Stack
* React
* React Router
* Web3Modal
* Ethers
* Babel
* Webpack
* TypeScript
* Material Tailwind
* Speechly

## Getting Started
To get started with the project, run the following commands:
```bash
npm install
npm run lint:error
npm run checktypes
npm run start
```
This will install the dependencies, check for linting errors, check the types, and start the development server. The application will be available at http://localhost:8080.