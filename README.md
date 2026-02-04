# Mini Browser

A simple custom browser UI built with Electron for experimentation and learning.

## Prerequisites

- **Node.js** installed
- **VS Code** (optional, for development)

## Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Run the browser:

   ```bash
   npm start
   ```

## Features

- Simple address bar for navigation
- Renders web pages in a custom shell
- Press Enter or click "Go" to navigate to URLs
- URLs without protocol automatically get `https://` prepended

## Project Structure

- `main.js` - Electron main process
- `preload.js` - Preload script for exposing APIs to renderer
- `index.html` - Browser UI with address bar

## What this browser can do

- Render web pages in a custom shell
- Let you experiment with UI, navigation, and integrations
- Use standard HTTP/HTTPS like any other app

## License

MIT