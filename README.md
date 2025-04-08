# 🧠 AI-Powered Research Agent  
### Automated Web Search and Summarization using Brave Search API and GPT

A fully autonomous research assistant built with Python that performs real-time information retrieval and summarization using **Brave Search API**, **content parsing**, and **OpenAI's GPT models**. This notebook demonstrates how LLMs can be combined with modern APIs to produce structured, high-quality research summaries with minimal human input.

---

## 🚀 What It Does

1. Accepts a user-defined research topic or query.
2. Uses the **Brave Search API** to fetch relevant and recent web links.
3. Parses full article content using `newspaper3k` and cleans it.
4. Sends content to **OpenAI's GPT model** for summarization.
5. Outputs a structured research report from multiple sources.

---

## 🎯 Why It Matters

This project is designed to simulate how a human might perform a focused web-based literature review — but automated using real-time APIs and generative AI.

It demonstrates:
- Practical integration of multiple APIs in a pipeline.
- Applied knowledge of LLMs for real-world tasks.
- Clean, modular Python design inside a single reproducible notebook.
- Efficient handling of unstructured web content.

---

## 🧠 Technologies Used

| Purpose             | Tools & Libraries              |
|---------------------|--------------------------------|
| Web Search          | `Brave Search API`             |
| Article Parsing     | `newspaper3k`, `requests`      |
| Summarization (LLM) | `openai` Python SDK (GPT)      |
| Dev Environment     | `Python`, `Jupyter Notebook`   |

---

## 🛠️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/AI_Powered_Research_Agent.git
   cd AI_Powered_Research_Agent
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Environment Variables**
   Either set these in your terminal or store them in a `.env` file:
   ```bash
   export OPENAI_API_KEY="your_openai_key"
   export BRAVE_SEARCH_API_KEY="your_brave_api_key"
   ```

4. **Run the Notebook**
   Launch the notebook and execute cells step-by-step:
   ```bash
   jupyter notebook AI_Powered_Research_Agent.ipynb
   ```

---

## 💡 Potential Applications

- Academic research & literature review
- Competitive and market analysis
- News aggregation with synthesis
- Quick topic briefings using LLMs

---

## ✅ Next Steps / Improvements

- Add caching for repeated queries
- Enable long-form summarization with chunking
- Rank sources by domain trust score
- Build CLI or lightweight UI with Streamlit

---

## 🧬 About the Author

Engineer-turned-analyst with a strong foundation in:
- Full-stack development and automation
- Data science and LLM-based tools
- Building usable AI products from scratch

Currently exploring real-world applications of generative AI in productivity and research workflows.

---

## 🪪 License

MIT License — open for use, modification, and collaboration.
