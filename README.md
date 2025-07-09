# 🧠 AI Interview Agent

An interactive AI-powered interview simulation system built using large language models (LLMs) and Gradio. This project enables users to practice interviews in a conversational format with an AI agent that can ask questions, evaluate answers, and provide personalized feedback.

---

## 📌 Project Overview

**AI Interview Agent** is designed to simulate real interview scenarios using natural language processing. It allows users to engage with an AI that takes on the role of an interviewer, generating relevant questions and evaluating responses in real-time. The system is implemented using OpenAI's GPT model and a user-friendly Gradio interface.

This project can be extended for:
- Job seekers preparing for behavioral or technical interviews
- AI coaching platforms
- Automated candidate screening tools

---

## ✨ Key Features

- 🗣️ **Conversational Interview Simulation**  
  Engage in natural language interviews with an AI agent that dynamically adjusts its questions.

- 🎯 **Answer Evaluation & Feedback**  
  The system analyzes user responses and provides brief feedback or suggestions for improvement.

- 🧠 **Customizable Roles & Job Context**  
  Users can select the type of job or role to receive tailored interview questions.

- 🌐 **Gradio-based Web UI**  
  No need to run in the terminal — everything is accessible via a simple web interface.

---

## 🛠️ Tech Stack

| Component        | Description                            |
|------------------|----------------------------------------|
| 🧠 LLM API        | OpenAI GPT-3.5 / GPT-4                 |
| 🧪 Notebook       | Jupyter Notebook (for prototyping)     |
| 🎨 Interface      | Gradio                                |
| 🐍 Language       | Python                                 |
| 📦 Libraries      | `openai`, `gradio`, `langchain`, `dotenv` |

---

## 📂 File Structure

```bash
.
├── AI Interview Agent_with_Gradio.ipynb   # Gradio UI implementation
├── AI Interview Agent_v2_0.ipynb          # Core logic and LLM interaction
├── .env                                   # API Key (not included)
├── requirements.txt                       # Required Python packages

---

🚀 How to Run
1. Clone this repo
```python
git clone https://github.com/yourusername/ai-interview-agent.git
cd ai-interview-agent
```

2. Install dependencies
```python
pip install -r requirements.txt
```

3. Set your OpenAI API key
Create a .env file with the following format:
OPENAI_API_KEY=your_api_key_here


4. Run the Gradio App
You can either open AI Interview Agent_with_Gradio.ipynb and run all cells in Jupyter,
or convert it to a .py script and launch:
```python
python app.py
```
