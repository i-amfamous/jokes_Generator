# Jokes Generator
https://i-amfamous.github.io/jokes_Generator/

A simple web app that fetches and displays random jokes from the JokeAPI. It is built with plain HTML, CSS, and JavaScript, and is designed to be easy to run locally without any setup or backend.

## Features

- Generate a random joke with one click
- Clean, lightweight front-end experience
- Responsive layout for desktop and mobile
- No dependencies or build tools required

## Tech Stack

- HTML
- CSS
- JavaScript
- JokeAPI

## Project Structure

- `index.html` — app layout and button container
- `style.css` — page styling and design
- `script.js` — joke-fetching logic
- `jokes.jpg` — project image asset

## How to Run

Because this is a static site, you can run it in two simple ways:

1. Open `index.html` directly in your browser.
2. Or serve it locally:

```bash
cd jokes_Generator
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Usage

- Click the "Get a joke" button to fetch a new random joke.
- The app will display either a single-line joke or a setup/delivery joke depending on the response from the API.

## Notes

This project uses the public JokeAPI service, so an internet connection is required for the app to fetch jokes.

## License

This project is for personal or educational use. Add a license here if you plan to share or distribute it publicly.
