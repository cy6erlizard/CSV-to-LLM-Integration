# CSV to LLM Integration

## Overview

The **CSV to LLM Integration** project bridges structured data stored in CSV files with a powerful language model (LLM). This integration allows users to ask natural language questions about the data and receive accurate and insightful answers. The goal is to make data exploration and insights accessible to anyone, regardless of technical expertise.

## Demo Video

Watch the demo video to understand how the project works:

[![CSV to LLM Demo]](https://www.loom.com/share/edcaa76e2969444c81033cdf877a005b?sid=a5eb878f-20ad-438e-b3a1-c02c8c8375a3)

Click the thumbnail above to watch the video.

## Main Functionality

- **Data Loading**: Import and process CSV files for analysis.
- **Question and Answer**: Users can query the LLM in plain English to retrieve insights from the CSV data.
- **Dynamic Analysis**: Perform dynamic computations such as averages, maximum/minimum values, filtering, and more based on user questions.
- **Interactive Interface**: Provide a conversational interface for seamless interaction with the dataset.
- **Integration with Google Sheets**: Log questions and answers into a Google Sheet for record-keeping and further analysis.

## Goal of the Project

The main goal of this project is to simplify data analysis by:
1. Allowing users to interact with data using plain language questions.
2. Automating insights and reducing the need for manual data exploration.
3. Enabling easy logging and tracking of queries and insights in Google Sheets.

## Key Features

1. **Natural Language Queries**: Users can ask questions like:
   - What is the highest value in column X?
   - Which rows match a specific condition?
   - What is the average price of properties?

2. **Google Sheets Logging**:
   - Store questions, answers, and timestamps in a Google Sheet for auditing and reporting.

3. **Dynamic and Scalable**:
   - Adaptable to various datasets, enabling users to explore diverse CSV files with ease.

4. **Python Notebook Framework**:
   - Fully integrated into a Jupyter Notebook environment, making it easy to extend and adapt.

## Installation

1. Clone the repository or download the project files.
2. Install the required Python libraries:
   ```bash
   pip install pandas gspread oauth2client openai
