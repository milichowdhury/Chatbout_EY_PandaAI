# Chatbout_EY_PandasAI
#### This project demonstrates the implementation of an AI-powered chatbot for interacting with data from CSV files using PandasAI, ChatGroq, and Streamlit for the frontend. The chatbot enables users to query CSV data using natural language and get responses in the form of visualizations and tables, enhancing the experience of exploring and understanding data.
## Key Technologies Used
#### PandasAI: An extension of the Pandas library that allows for natural language querying of data stored in DataFrames. It simplifies data analysis tasks by enabling users to ask questions in plain language instead of writing complex code.
#### ChatGroq: A language model that powers the natural language processing (NLP) capabilities of the chatbot. It interacts with the data, processes the user queries, and provides accurate responses.
#### Streamlit: A framework used to build the web-based interface for uploading CSV files and interacting with the chatbot.
#### LLAMA3-Groq: The specific model used in ChatGroq to process language queries and retrieve meaningful insights from the data.
## Features
#### Uploaded CSV files for processing and analysis.
#### Queried data in natural language without the need for explicit Python code.
#### Generated charts and graphs (e.g., scatter plots) on-demand based on user queries.
##### Retrieved data in tabular format, filtered according to user inputs.
## Prerequisites
#### Python 3.8 or higher
#### Pip package manager
#### Environment variables for GROQ_API_KEY setup
#### CLoned the repository
#### Installed required dependencies by requirement.txt 
#### Set up the env throught Groq API key
#### run the application in streamlit
## How to use
#### Upload CSV File: Use the interface to upload your CSV file.
#### Ask Queries: Enter natural language queries such as:
####  "Show scatter plot for air temperature and process temperature."
#### "Give all product IDs where process temperature is above 311.1."
## View Responses: 
##### Based on our query, the chatbot will either return data in a table or generate visualizations.
