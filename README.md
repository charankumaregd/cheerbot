# CheerBot

A mental wellness chatbot prototype built using HTML, CSS, and JavaScript.

## Project Overview

CheerBot is a web-based chatbot concept designed to provide a friendly conversational experience. It explores basic chatbot interactions and browser-based speech synthesis.

## Features

- **Sign-in / Sign-up Interface:** Animated landing page with a sliding login and registration interface.
- **Rule-Based Chatbot:** Matches user messages against predefined prompts and responds with predefined replies.
- **Text-to-Speech:** Uses the browser's Web Speech API to read chatbot responses aloud.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Web Speech API

## Project Structure

```text
cheerbot/
├── css/
│   ├── stylesheet1.css
│   └── stylesheet2.css
├── images/
│   ├── facebook-app-symbol.png
│   ├── google.png
│   ├── logo.png
│   ├── twitter.png
│   └── user.png
├── js/
│   └── speech.js
├── pages/
│   └── chat.html
├── index.html
└── README.md
```

## Running Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/charankumaregd/cheerbot.git
   cd cheerbot
   ```

2. Open the project using a local development server, such as the VS Code Live Server extension.

3. Open the local URL in a browser to explore the prototype.

## Implementation Notes

- Chatbot responses are based on predefined JavaScript prompt and reply arrays, not an AI model.
- The sign-in and sign-up screens are interface demonstrations; authentication is not connected to a backend.
- Speech output depends on browser support.

## Disclaimer

CheerBot is an experimental prototype and is **not a professional mental health service, clinical tool, or crisis support system**. It should not be relied upon for mental health advice or emergency assistance.