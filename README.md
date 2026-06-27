🚨 TriangleAi
An AI-powered IT Log Triage System built with Node.js and Groq.

https://triangle-ai.onrender.com/


🎯 The Problem
Enterprise companies receive thousands of messy, unstructured error logs and IT tickets. Human agents waste hours reading and categorizing them before work can begin.

💡 The Solution
TriangleAi is an enterprise-grade triage engine. A user pastes a messy log, and the AI instantly parses it, categorizes the issue, assigns a priority score (1-10), and applies business logic to determine the escalation status.

🧠 Key Features & Skills Demonstrated
AI Integration: Successfully integrated the Groq API (Llama 3) using the industry-standard OpenAI format.
Prompt Engineering: Engineered a strict system prompt to force JSON output and prevent AI hallucinations (e.g., ensuring a "fire" gets a 10, not a 1).
Computational Thinking: Built a backend logic layer (if/else algorithms) that takes raw AI data and applies real-world business rules to determine SLA status (Critical, Normal, Low).
Dynamic Frontend Logic: Vanilla JavaScript parses the JSON response and dynamically alters the UI state (changing background colors) based on data constraints.
🛠️ Tech Stack
Backend: Node.js, Express
AI Engine: Groq (Llama-3-8b)
Frontend: HTML, CSS, Vanilla JavaScript (No frameworks, raw fundamentals)
🚀 How to Run
Clone the repo: git clone <your-repo-link>
Install dependencies: npm install
Create a .env file and add your Groq API key: GROQ_API_KEY=your_key_here
Start the server: node server.js
Open index.html in your browser.
