# Financial Report Analyzer AI Agent using LangChain

## Introduction

Extracting insights from financial reports is crucial for informed decision-making. This project demonstrates how to build an AI-powered financial analyst that extracts text from a PDF, processes it using a conversational agent, and generates financial summaries, trends, and insights. To understand the code in this repository step-by-step, read the article [How to Build LangChain Agents by ProjectPro](https://www.projectpro.io/article/how-to-build-langchain-agents/1099)

## Features

- Extracts text from financial reports in PDF format
- Uses an AI model to analyze financial data
- Provides structured insights on revenue trends and key metrics
- Remembers past interactions for contextual understanding
- Summarizes financial data in response to user queries

## Steps to Build the Agent

1. **Install Dependencies** – Set up the required Python packages
2. **Extract Text from PDF** – Process financial reports using PyMuPDF
3. **Set Up Groq API Key** – Authenticate and initialize the AI model
4. **Initialize AI Model and Memory** – Ensure the agent retains conversation history
5. **Define Financial Analysis Tool** – Create a function for extracting insights
6. **Build the AI Agent** – Integrate tools with a conversational AI agent
7. **Run the Agent** – Query the AI to analyze and summarize financial data

## Prerequisites

- Python 3.8+
- Groq API Key
- Financial report in PDF format

## Usage

1. Install the required dependencies.
2. Provide the path to the financial report PDF.
3. Run the script to analyze and extract key insights.
4. Ask the AI agent for financial summaries, trends, and analysis.

## Data Source
The file has been downloaded using this link: [Meta Q1 2024 Financial Report](https://s21.q4cdn.com/399680738/files/doc_financials/2024/q1/Meta-03-31-2024-Exhibit-99-1_FINAL.pdf).

## Future Enhancements

- Expand analysis capabilities beyond financial reports.
- Integrate with real-time financial data sources.
- Improve natural language understanding for better insights.
