# Natural-Language-to-SQL-AI-Agent (n8n automation)

# Project Overview

This project demonstrates an AI-powered data assistant that converts natural language questions into SQL queries and retrieves results automatically.

The system allows users to ask business questions in plain English, which are then interpreted by a language model to generate SQL queries that run against a structured dataset.

The workflow is implemented using n8n, enabling a visual automation pipeline without traditional application code.

The goal of this project was to simulate how modern organizations can enable self-service analytics using AI-powered data assistants.

# Problem Statement

Business users often need insights from databases but may not know SQL.

This project solves that problem by creating a system where users can ask questions such as:

“Which city generated the highest revenue?”
“What is the total revenue this month?”

The AI system automatically:

Interprets the natural language query
Converts it into SQL
Executes the query on the dataset
Returns the result to the user

# Workflow Explanation

User Input
The user submits a natural language question.

LLM Processing
The language model interprets the question and generates the appropriate SQL query.

Query Execution
The generated SQL query runs against the structured dataset.
The database returns the relevant result.

Output Response
The system sends the query result back to the user as a response.

# Tech Stack

Automation
n8n workflow automation
AI / Language Model
Large Language Model (LLM) for query generation

Database
Structured relational dataset

Concepts Used
Natural Language Processing
AI-assisted query generation
Workflow automation
Self-service analytics

# Key Learning Outcomes

This project demonstrates:
Designing AI-powered data assistants
Building automation workflows using n8n
Implementing Natural Language to SQL conversion
Integrating LLM capabilities into analytics workflows
Creating self-service data query systems
