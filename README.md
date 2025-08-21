# 🧠 Candilyzer

**AI-Powered GitHub & LinkedIn Candidate Analyzer**

A Streamlit app that uses AI agents to analyze technical candidates based on their GitHub repositories and LinkedIn profiles. Provides detailed evaluations, skill assessments, and scoring for tech hiring decisions.

## 🚀 Quick Start

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Get API Keys
- **Nebius API Key**: [Get from Nebius AI Studio](https://studio.nebius.com/?modals=create-api-key)
- **GitHub API Key**: [Generate Here](https://github.com/settings/tokens)
- **Exa API Key**: [Get from Exa](https://exa.ai)

### 3. Run the App
```bash
streamlit run main.py
```

## ✨ Features

- **Multi-Candidate Analyzer**: Compare multiple GitHub users side-by-side
- **Single Candidate Profiler**: Deep analysis of one candidate's profiles
- **AI-Powered Scoring**: 0-100 scoring system with detailed justifications
- **GitHub Integration**: Analyzes repositories, commits, and code quality
- **LinkedIn Analysis**: Professional background verification via Exa search

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **AI Framework**: Agno Agents
- **Model Provider**: Nebius (DeepSeek models)
- **Tools**: GitHub API, Exa Search, Reasoning Tools

## 📊 How It Works

1. Enter GitHub usernames and target job role
2. AI agent analyzes repositories, code quality, and activity
3. Cross-references LinkedIn profiles for professional verification
4. Provides comprehensive scoring and hiring recommendations
5. Uses strict criteria to filter only top-tier candidates

## 🔑 Model ID

For the Model ID field, try:
- `deepseek-chat`
- `deepseek-coder`

Check your Nebius dashboard for the exact available model IDs.

---
