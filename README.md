# ai-guardrail-scanner
An automated, GUI-based AI Red Teaming tool built with Python to test LLM security guardrails and prompt injection vulnerabilities.

# ⚔️ AI Guardrail Scanner & Red Teaming Arena v1.0

An automated, GUI-based AI Red Teaming tool designed to test Large Language Model (LLM) security boundaries, prompt injections, and guardrail mechanisms.

## 🚀 Key Features
- **Dynamic Prompt Combination:** Automatically generates diverse adversarial test cases by combining custom prefixes and attack vectors.
- **Real-Time Guardrail Analysis:** Pinpoints exactly which keywords or payloads trigger the AI model's security filters.
- **Cyberpunk GUI:** Built with Python's Tkinter framework to provide a clean, responsive, and intuitive interface for security testing.

## 💻 Tech Stack
- Python 3.x
- Tkinter (GUI Engine)
- Time & Random Modules

## 🛠️ How to Run

1. Make sure you have Python installed on your system.
2. Clone this repository or download the `arena.py` file.
3. Open your terminal or command prompt, navigate to the file directory, and run the following command:

```bash
python arena.py

Last Information;

---

### 📝 Summary

This project is a simple simulation tool to understand how modern AI models protect themselves from prompt injections. 

It demonstrates two main security types used by top AI models:
- **Input Filters:** Stopping bad words before the AI processes them (like **OpenAI GPT-4o** and **Azure AI** systems).
- **Output Alignment:** The AI understands the question but refuses to answer due to safety rules (like **Anthropic Claude** and **Google Gemini**).

*This tool is created for educational purposes and AI Red Teaming research.*
