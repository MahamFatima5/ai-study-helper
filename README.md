# AI Study Helper

A simple AI-powered web app that helps students study. Paste your notes, pick a mode, and the AI will explain them simply, summarize them, or turn them into a quiz.

Built as the **Module 5 (AI Tools & Mini Project)** submission for the Codomax Digital Solutions internship.

## Features
- **Explain simply**: breaks down any topic in beginner-friendly words
- **Summarize**: turns notes into 5 short bullet points
- **Make a quiz**: generates a 5-question multiple-choice quiz with answers
- Notebook-style notes area with ruled lines and a highlighter-style mode selector
- Formatted results with bullets, numbered questions, and highlighted key terms
- Loading animation while the AI is working
- One-click **Copy** button for the results
- Live word counter and a **Use sample** button
- Clear error messages
- Responsive design that works on phones and laptops

## Tech Stack
- HTML, CSS, and vanilla JavaScript (single `index.html` file, no build step)
- [Groq API](https://console.groq.com) running OpenAI's open-weight model `gpt-oss-120b`
- Google Fonts: Bricolage Grotesque and Figtree

## How It Works
1. The user pastes text and selects a mode.
2. The app builds a prompt for that mode and sends it to the Groq chat completions API.
3. The AI's answer is formatted safely (without injecting raw HTML) and shown in the results panel.

## How to Run
1. Get a free API key from [console.groq.com/keys](https://console.groq.com/keys).
2. Open `index.html` in a browser, or run the project on StackBlitz.
3. Select **API key** at the top and paste your key. It is saved only in your browser and is never stored in the code.
4. Paste some notes, choose a mode, and click **Generate**.

## AI Tools I Explored
- ChatGPT and Gemini for brainstorming and understanding concepts
- Groq for fast AI model inference
- Claude for help with coding, design, and debugging

## What I Learned
- Connecting a web app to an AI model through an API
- Writing clear prompts for different tasks
- Handling loading states, errors, and API keys safely in the browser
- Using AI tools to speed up development while understanding the code

## Author
**Maham Fatima**
[LinkedIn](https://www.linkedin.com/in/maham-fatima-705144394/)
