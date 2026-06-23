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
1. Make sure you have Python installed.
2. Run the following command in your terminal:
```bash
python arena.py


LAST INFORMATION


## 🔍 Real-World Guardrail Landscape

This tool is designed to simulate attack vectors against the two primary types of AI safety systems found in industry-leading LLMs:

1. **Input Filtering (Prompt Shielding):** - Found in models like **OpenAI's GPT-4o (via Moderation API)** and **Microsoft Azure AI Content Safety**.
   - These systems intercept the prompt *before* it reaches the model core. Our tool simulates this by catching keywords like `"password"` or `"leak"` instantly.

2. **Output Alignment (Reinforcement Learning - RLHF):**
   - Found in models like **Anthropic's Claude 3.5 Sonnet** and **Google's Gemini 1.5 Pro**.
   - These models process the prompt but refuse to comply during generation (e.g., *"I cannot fulfill this request"*). Our tool tracks these via the simulated `Target AI Response` log.
