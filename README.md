🔴 DualChat - Genjutsu Edition 🔴

Welcome to DualChat, a lightning-fast, real-time chat application featuring a stark, bold Neo-Brutalist aesthetic. Connect with the community in a live public room, or switch to the AI tab for a private conversation with a highly intelligent, context-aware AI assistant.

🚀 Play with the Live Demo Here!

✨ Features

Two Modes, One App: Seamlessly toggle between a live Community Chat and a private AI Assistant Chat without losing your place.

Neo-Brutalist UI: A heavy, bold, high-contrast design featuring stark borders, hard shadows, and a distinct "Genjutsu" red/black/yellow color palette.

Context-Aware AI: The AI reads the recent community messages and knows your name, allowing for dynamic, contextual conversations.

Rich Text & Codeblocks: The chat natively supports markdown! You and the AI can use **bold**, __underline__, _italics_, bullet points, and render beautiful hacker-style codeblocks.

Smart Scrolling: Read past messages in peace. The auto-scroll pauses if you scroll up, providing a custom "jump to bottom" button when new messages arrive.

Persistent Memory: Your AI chat history and display name are securely saved to your local browser storage.

🛠️ Built With

Frontend: HTML5, Vanilla JavaScript, Tailwind CSS (via CDN), FontAwesome.

Backend / DB: Cloudflare Workers (for community chat persistence).

AI Engine: Groq API running openai/gpt-oss-120b.

⚠️ QUICK START & SETUP WARNING

To run this project locally or fork it for your own use, you must configure your own AI API Key.

🛑 CRITICAL STEP: Add Your Groq API Key

Before deploying or running locally, you need to add your personal Groq API key to the code.

Open index.html.

Scroll down to the JavaScript section (around Line 123).

Locate the GROQ_API_KEY constant.

Replace the existing key placeholder with your actual Groq API key.

// CHANGE THIS LINE IN YOUR CODE:
const GROQ_API_KEY = "YOUR_OWN_GROQ_API_KEY_HERE";


Note: For a production-ready application, it is highly recommended to move your API key to a secure backend environment to prevent it from being exposed in the frontend code.

💻 How to Run Locally

Clone this repository:

git clone [https://github.com/sawyerbobk563-code/dualchat.git](https://github.com/sawyerbobk563-code/dualchat.git)


Navigate into the project folder.

Open index.html in any modern web browser.

Enjoy!
