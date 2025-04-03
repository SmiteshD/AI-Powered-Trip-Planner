# AI-Powered Trip Planner

## 📌 Overview
An AI-driven travel assistant that personalizes trip planning by providing itinerary suggestions, travel logistics, and local recommendations based on user preferences.

## 👩‍💻 Tech Stack
Streamlit, Python, CrewAI, LangChain, Ollama, Deepseek-R1:1.5b, DuckDuckGo Search

## 🚀 Features
**Personalized Itinerary Generation:** Creates customized travel plans based on user input.

**Multi-Agent Collaboration:** Uses specialized AI agents for location insights, activity recommendations, and itinerary structuring.

**Real-Time Web Search:** Fetches updated travel information using DuckDuckGo search.

**Interactive Streamlit UI:** Provides an intuitive interface for users to enter travel details and receive instant plans.

**Markdown Report Generation:** Outputs structured travel plans for easy sharing and downloading.

## 🛠️ Setup Instructions

1️⃣ **Clone the Repository**

```bash
git clone <your-repo-url>
cd <repo-folder>
```

2️⃣ **Install Dependencies**

```bash
pip install -r requirements.txt
```

3️⃣ **Run Ollama Locally (Ensure Ollama is installed and running)**

```bash
ollama serve
```

4️⃣ Start the Streamlit App

```bash
streamlit run app.py
```

## 🏗️ Project Structure

```bash
├── agents.py          # Defines AI agents for different trip planning tasks
├── tasks.py           # Task definitions for each AI agent
├── tools.py           # Custom tools for web search integration
├── app.py             # Streamlit-based user interface
```

## 🎯 How It Works

- Enter travel details (departure city, destination, dates, interests) in the Streamlit UI.

- AI agents collaborate to gather travel logistics, attractions, and create an itinerary.

- Receive a well-structured plan with markdown formatting.

- Download the travel plan for offline use.

## 📌 Future Enhancements

- Integration with flight and hotel booking APIs.

- Multi-language support for non-English users.

- Advanced budget estimation and currency conversion.

