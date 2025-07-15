# ✨ A Practical Guide to Building AI Agents

An interactive dashboard and AI-powered designer that demystifies agentic AI, synthesizing best practices from Google and OpenAI to turn ideas into actionable architecture.

## 🧠 What This Project Does

This tool serves as an end-to-end guide for project managers, developers, and AI enthusiasts to design and prototype autonomous AI agents. It allows users to:
- **Learn the fundamentals** of agentic AI through an interactive dashboard covering core components, tools, orchestration patterns, and safety guardrails.
- **Translate a problem into a plan** by simply describing a challenge in plain language.
- **Receive a complete agent architecture** designed by AI, outlining the agent's goal, recommended tools, orchestration pattern, and safety considerations.
- **Generate starter Python code** based on the proposed architecture to kickstart the development process.

## 🎯 Why It Matters

"Agentic AI" is set to drive the next wave of automation, but it's a new and often abstract field. For many teams, the biggest challenge isn't the technology itself, but knowing **where to start**. How do we translate a business need into a viable technical design for an AI agent?

As a Project Manager focused on digital transformation at Air Liquide Japan, I've experienced this firsthand. We need to rapidly evaluate ideas, align stakeholders on a technical approach, and estimate feasibility—long before extensive development begins.

I built this tool to solve that problem. It's a bridge from concept to code, designed to make AI agent design less of a "black box" and more of a structured, accessible process. It helps teams visualize an agent's architecture, understand its components, and get a tangible starting point in minutes.

> 💡 This project isn't just about generating code; it's about building understanding and enabling better planning for technology-driven innovation.

## 🚀 Features

- ✨ **AI-Powered Agent Designer** — Describe a problem and receive a complete, high-level agent architecture.
- 🐍 **Python Starter Code Generation** — Go from architecture to starter code with a single click.
- 📚 **Interactive Learning Dashboard** — Explore the core concepts of agent design through clickable diagrams and cards.
- 🛡️ **Built-in Best Practices** — Content covers essential topics like Guardrails, Orchestration Patterns, and the "Pyramid of Trust" in AI.
- 🎓 **Curated Learning Center** — Features clear, concise explanations of key terms and concepts in an easy-to-navigate accordion format.
- 📱 **Fully Responsive Design** — Works seamlessly on desktop, tablet, and mobile devices.

## 🔎 Example Use Cases

- "I need to build an agent to handle customer service refund requests." → The tool designs a "Manager Pattern" agent that uses a **Data Tool** to check order history, an **Action Tool** to process the refund in a payment system, and another to send a confirmation email.
- "Design an agent that proactively monitors our industrial gas supply levels and alerts the logistics team." → It suggests a design with **Guardrails** to prevent accidental re-orders and **Tools** to access inventory databases and send SMS alerts.
- "I'm a student and I just want to understand what an AI agent is." → The user can browse the "Learning Center" and "Core Components" tabs to grasp the fundamentals without using the AI designer.

## 🛠️ Tech Stack / Tools Used

- HTML, Tailwind CSS, Vanilla JavaScript
- Gemini API for agent architecture design and Python code generation
- Fully client-side logic in a single-page application (SPA) format
- Fixed header and footer for a professional, branded experience

## 🌐 Live Demo

👉 [https://khanhaissam.github.io/guide-to-building-agents/](https://khanhaissam.github.io/guide-to-building-agents/)

## 🧪 How to Run This Project

> No complex setup needed! This project is a single HTML file and runs entirely in the browser.

1.  Clone the repository: `git clone https://github.com/khanhaissam/guide-to-building-agents.git`
2.  Navigate to the project directory.
3.  Open the `index.html` file in your preferred web browser.

### 🔑 Enable AI Features (Optional)

The core educational content works offline, but to use the "Agent Designer" and other AI-powered features, you'll need a Gemini API key.

1.  Get a free API key at [Google AI for Makers](https://makersuite.google.com/).
2.  In the `index.html` file, find the `<script>` tag at the bottom.
3.  Locate this line:
    ```javascript
    const apiKey = ""; // API key will be injected by the environment
    ```
4.  Replace the empty quotes with your API key:
    ```javascript
    const apiKey = "YOUR_GEMINI_API_KEY";
    ```
5.  Save the file and refresh your browser. The AI features will now be active.
