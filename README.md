# 🚀 Advanced LangChain Workflows

This repository demonstrates various advanced LangChain workflows for structured AI-driven outputs, utilizing Google Gemini, OpenAI, and Anthropic models. The examples cover sequential and parallel processing, conditional chains, and structured data generation.

---

## 📁 Repository Structure

| File                       | Description                                                                                                                        |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **simple\_chain.py**       | Implements a basic LangChain pipeline using Google Gemini to generate structured facts about a given topic.                        |
| **sequential\_chain.py**   | Demonstrates a sequential pipeline where one model generates a detailed report, and another summarizes it into five key points.    |
| **parallel\_chains.py**    | Uses parallel chains to simultaneously generate notes and quiz questions from a text, then merges them into a structured document. |
| **conditional\_chains.py** | Implements a conditional chain that classifies feedback sentiment and generates appropriate responses based on sentiment analysis. |

---

## 🔧 Tech Stack

- **LangChain** — AI workflow orchestration
- **Google Gemini (PaLM)** — LLM inference via `langchain-google-genai`
- **OpenAI GPT** — Alternative LLM backend
- **Anthropic Claude** — Used for advanced AI processing
- **Pydantic** — Structured validation for output enforcement
- **Python-dotenv** — Environment variable management

---

## 🚀 Quick Start

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/advanced-langchain-workflows.git
   cd advanced-langchain-workflows
   ```

2. Create & activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Add your API keys to a `.env` file:

   ```
   GOOGLE_API_KEY=your_gemini_api_key_here
   OPENAI_API_KEY=your_openai_api_key_here
   ```

5. Run any example script:

   ```bash
   python simple_chain.py
   python sequential_chain.py
   python parallel_chains.py
   python conditional_chains.py
   ```

---

## 📄 License

MIT © 2025

## 📫 Contact

Questions or feedback? Email **[haseebulhassan1172003@gmail.com](mailto\:haseebulhassan1172003@gmail.com)**.

