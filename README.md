# amaan-voice-bot

# Amaan's Voice Bot
Amaan's Voice Bot is a web-based, AI-powered voice assistant designed to answer interview questions as Shaikh Mohammad Amaan, an AI practitioner. Built with HTML, CSS, and JavaScript, it uses the Web Speech API for voice input/output and integrates with the Gemini API for dynamic responses. The app features a polished, user-friendly interface with a greeting message, responsive design, and conversation history.
Features

Voice Interaction: Users can speak questions, and the bot responds with synthesized speech.
Predefined Responses: Hardcoded answers for specific questions about Amaan's background, skills, and goals.
Dynamic Responses: For unhandled questions, the bot queries the Gemini API with context for consistent, professional responses.
Conversation History: Displays past questions and answers, with clickable entries to replay responses.
Accessible Design: Includes ARIA attributes and keyboard navigation for accessibility.
Responsive UI: Optimized for both desktop and mobile devices with a modern, card-based layout.

# Prerequisites

A modern web browser (e.g., Chrome, Firefox, Edge) that supports the Web Speech API.
An active internet connection for API requests.
A valid Gemini API key (replace the placeholder key in the code with your own).

# Setup Instructions

# Clone or Download the Repository:

Clone the repository from GitHub or download the index.html file.
Ensure you have the index.html file, which contains all HTML, CSS, and JavaScript.


# Host the Web App:

# Local Hosting:
Place index.html in a directory.
Use a local server (e.g., python -m http.server 8000 or npx serve) to serve the file.
Open http://localhost:8000 in your browser.


# Online Hosting (Recommended for Submission):
Push the index.html file to a GitHub repository.
Deploy using a static hosting service like Vercel, Netlify, or GitHub Pages:
Vercel: Create a new project, link your GitHub repo, and deploy.
Netlify: Drag and drop the index.html file or link your GitHub repo.
GitHub Pages: Enable GitHub Pages in your repository settings and set the branch to main.


Obtain the public URL (e.g., https://your-app.vercel.app).




# Configure the Gemini API Key:

Replace the placeholder API key in the index.html file (AIzaSyAwm3T6siQ3_boc-UwyYdgKlOlA7IiiU8U) with a valid Gemini API key.
For production, secure the API key by proxying requests through a backend server to avoid exposing it in client-side code.



# Usage

Access the App:
Open the deployed URL or local server URL in a supported browser.


Interact with the Bot:
On page load, the app displays a welcome message: "Hello! I'm Amaan's AI voice bot, ready to answer your questions. Click the button below to start talking!"
Click the "Start Talking" button to begin voice input (ensure microphone permissions are granted).
Speak a question clearly (e.g., "What should we know about your life story?").
The bot will process the question, display the transcribed text, and respond via text and speech.
If the question matches a predefined response, it uses the hardcoded answer; otherwise, it retroactively searches the web for the most relevant information, it queries the Gemini API.


View History:
Questions and answers are logged in the "Conversation History" section.
Click any history item to replay the response via speech.


Stop Talking:
Click the "Stop Talking" button to pause voice input.



# Example Questions

What should we know about your life story in a few sentences?
What’s your #1 superpower?
What are the top 3 areas you’d like to grow in?
What misconception do your coworkers have about you?
How do you push your boundaries and limits?

# Notes

Browser Compatibility: The Web Speech API works best in Chrome and Edge. Test in multiple browsers for compatibility.
Accessibility: The app includes ARIA attributes and keyboard navigation. Ensure your browser supports these features for the best experience.
Troubleshooting:
If voice input fails, check microphone permissions and browser support.



Deployment for Submission

Deploy the app on Vercel, Netlify, or GitHub Pages to obtain a public URL.
Ensure the app is accessible without requiring users to install software or have coding knowledge.

