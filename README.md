# nasa-explorer

# Fullstack React + Express App

Nasa-Explorer is a website that shows the interesting pictures captured by NASA, including the pictues taken by the Mars Rover. Additionally, the Near-Earth Objects are detailed. AI summarizes the pictures of the day to keep it creative. This project contains a React frontend and Node/Express backend.

## Features

- The main page of the application shows the discovery of the website with the key features.
- APOD Page (A Picture Of Day) shows the picture with additional details.
    - The HD picture can be downloaded.
    - We can share the picture of the day using the Share option.
    - We can mark it as a favourite.
    - The Explaination details the photo taken from Nasa web service.
    - The 'Summarize for me' feature uses AI (Hugging Face AI) to get a short description of the photo.

- The 'Mars Rover' Page shows the grid of the pictures taken by the Rover. Additional filters are provided to narrow down the desired pictures.
- The 'NEO' page shows the table of Near-Earth Objects (Refreshed Everyday).
    - Selecting an item shows a modal with more details and link to the source information.

- The website can be toggled between Light and Dark modes.
- The 'About', 'Contact' and 'Disclaimer' sections are displayed at the bottom of the website.
- Fun-facts are displayed at the bottom of the page.

## Deployment

- The website is hosted on Render:
https://nasa-explorer-frontend.onrender.com/


## StackBlitz Usage

- Open this project in StackBlitz (https://stackblitz.com/).
- StackBlitz will automatically run `npm install` and `npm start` from the root.
- Both frontend and backend will run concurrently.

## Local Usage

### Start Backend

```bash
cd backend
npm install
node app.js
```

### Start Frontend

```bash
cd frontend
npm install
npm start
```