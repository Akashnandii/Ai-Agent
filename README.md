# 🧠 AI Agent Workflow using n8n

This project demonstrates an AI-powered chat agent built using the **n8n workflow automation platform**. It integrates multiple tools and models to create an intelligent, real-time query responder with minimal code effort.  

> ⚠️ _Note: This project is not deployed due to hosting costs. However, users can clone the workflow and run it on their local or trial n8n instance._

---

## 🔧 Features

- **Chat-based Trigger System**  
  Responds automatically when a user sends a chat message.

- **Groq Chat Model Integration**  
  Acts as the primary AI engine to process natural language inputs.

- **Simple Memory Module**  
  Maintains short-term memory of the conversation flow.

- **SerpAPI Integration**  
  Searches the web for real-time information when required.

- **Calculator Node**  
  Solves mathematical expressions and numerical logic on the fly.

- **Visual Workflow Interface**  
  Entire setup is managed visually inside the n8n editor for easier understanding and debugging.

---

## 🛠️ Tech Stack

| Tool/Service    | Role                          |
|-----------------|-------------------------------|
| **n8n**         | Workflow automation platform  |
| **Groq Model**  | Chat-based AI model           |
| **SerpAPI**     | Google Search API integration |
| **Calculator**  | Math expression resolver      |
| **Simple Memory** | Short-term memory for chat history |

---

## 📸 Workflow Overview

![Workflow Screenshot]([./Ai Agent.png](https://github.com/Akashnandii/Ai-Agent/blob/main/Ai%20Agent.png))

![Workflow Screenshot]([./Ai Agent.png](https://github.com/Akashnandii/Ai-Agent/blob/main/input%2C%20output.png))

![Workflow Screenshot]([./Ai Agent.png](https://github.com/Akashnandii/Ai-Agent/blob/main/input%2Coutput.png))

> A visual representation of the workflow where "When chat message received" triggers the AI agent and distributes the message to tools like Groq Chat, SerpAPI, and Calculator.

---

## 🚀 How to Use This Project

1. **Install n8n (locally or on trial cloud):**  
   [https://n8n.io](https://n8n.io)

2. **Import the Workflow:**
   - Open n8n.
   - Click on "Import" and upload the `ai-agent-workflow.json` file provided in this repository.

3. **Configure API Keys:**
   - Set up your own keys for:
     - **SerpAPI**
     - (Optional) Any specific setup for the Groq model, if required.

4. **Run the Workflow:**
   - Set it to **Active**.
   - Trigger the input and view results in the execution log.

---

## 🧪 Limitations

- Not hosted live due to paid deployment (₹499/month on n8n Cloud).
- Groq model and other external tools may have rate limits or API key requirements.
- Suitable for demos, academic projects, or as a base for advanced AI workflows.

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `ai-agent-workflow.json` | Exported n8n workflow |
| `README.md` | Project documentation |
| `workflow-overview.png` | Screenshot of the workflow in n8n UI |

---

## 📌 Credits

Made by a Computer Science undergraduate passionate about AI/ML and workflow automation.  
If you liked this project, feel free to ⭐ the repo or connect!

---

## 📬 Contact

For feedback, collaboration, or questions:    
📱 LinkedIn: [(https://www.linkedin.com/in/akash-nandii)]

