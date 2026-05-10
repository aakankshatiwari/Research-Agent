AI Research Agent with Tool Calling & Autonomous Workflows

An end-to-end AI Agent project built using OpenAI API
 and Tavily AI
 that demonstrates how Large Language Models can autonomously use tools, search the web, extract webpage content, perform multi-step reasoning, and generate research reports.

This project is designed as a practical learning workflow for understanding:

Function Calling
AI Agents
Tool Orchestration
Autonomous Reasoning Loops
Real-time Web Research
Memory-driven Conversations
Report Generation Pipelines

🚀 Features
✅ OpenAI Function Calling Integration
✅ Real-time Web Search using Tavily
✅ Autonomous AI Agent Loop
✅ Multi-tool Reasoning Workflow
✅ Webpage Content Extraction
✅ Markdown Report Generation
✅ Career & Market Research Automation
✅ Tool Call Inspection & Debugging
✅ Iterative Decision Making
✅ Conversation Memory Tracking

🧠 What This Project Demonstrates

The project progressively evolves from:

A simple LLM call
Tool-enabled AI assistant
Multi-tool autonomous AI research agent
Career research & job intelligence system

The AI Agent can:

Search the internet
Read webpages
Analyze information
Make iterative decisions
Generate structured reports
Save outputs automatically

🏗️ Tech Stack
Python
OpenAI GPT-4o-mini
Tavily Search API
JSON Schema Function Calling
Markdown Report Generation

📂 Project Structure
├── main.ipynb / main.py
├── reports/
├── README.md
└── requirements.txt

⚙️ Installation

Clone the repository:

git clone <your-repo-url>
cd <your-project-folder>

Install dependencies:

pip install openai tavily-python

🔑 Environment Setup

Set your API keys before running:

from openai import OpenAI
from tavily import TavilyClient

OPENAI_API_KEY="your_openai_key"
TAVILY_API_KEY="your_tavily_key"

Or export them as environment variables:

export OPENAI_API_KEY=your_key
export TAVILY_API_KEY=your_key

🛠️ Tools Implemented
1. Web Search Tool

Searches the internet for real-time information.

search_web(query, max_results=5)
Example:
AI trends
Tech news
Job market research
Salary insights
2. Webpage Extraction Tool

Reads and extracts clean webpage content.

get_webpage_text(url)

Useful for:

Research analysis
Deep content extraction
Source validation
3. Report Saving Tool

Automatically saves AI-generated reports as Markdown files.

save_report(title, content)
4. Job Search Tool

Custom AI agent capability for career research.

search_jobs(role, location="India")

🔄 AI Agent Workflow

The autonomous loop works as follows:

User Query
   ↓
LLM Decides Tool
   ↓
Tool Executes
   ↓
Results Added to Memory
   ↓
LLM Re-evaluates
   ↓
More Tools OR Final Answer

The agent continues iterating until:

The task is completed
Or maximum iterations are reached

🤖 Example Research Queries
AI Job Market Research
Research the current state of AI job market in India in 2026.
Company Hiring Trends
Find top companies hiring AI Engineers in India.
Technology Comparison
Compare React vs Next.js vs Svelte in 2026.

📊 Agent Capabilities

The agent can:

Plan research steps
Decide which tool to use
Read multiple sources
Maintain conversation memory
Generate evidence-backed insights
Create structured reports

🧪 Learning Concepts Covered

This project is ideal for learning:

AI Agents
LLM Tool Calling
Autonomous Systems
Agentic AI
Retrieval-Augmented Generation (RAG)
Memory Handling
Multi-step Reasoning
Function Calling APIs
AI Workflow Orchestration

🎯 Sample Output

The agent can generate:

AI job market reports
Salary analysis
Skill recommendations
Company research
Career roadmaps
Industry trend summaries

📚 Key Learning Outcome

This project demonstrates how modern AI systems move beyond simple chatbots into autonomous agents capable of:

reasoning,
acting,
researching,
and executing workflows using external tools.

⭐ If You Found This Useful

Consider starring the repository and sharing it with others learning AI Agents and Agentic AI systems.
