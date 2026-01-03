# 🏥 Talk2Data: Natural Language to SQL Chatbot for Healthcare Analytics

## 📌 Project Overview
Talk2Data is a **conversational analytics chatbot** that allows users to query healthcare datasets using **natural language** instead of writing SQL manually.

The system integrates **Amazon Lex** for conversational intent handling, **AWS Lambda** for backend processing, and **OpenAI** for natural-language-to-SQL generation. User queries are dynamically converted into SQL and executed against **AWS RDS and Amazon Athena**, enabling real-time insights from healthcare data.

This project demonstrates how cloud services and large language models can be combined to build **scalable, user-friendly data access systems** for healthcare analytics.

---

## 🎯 Key Features
- Natural language to SQL query generation using OpenAI
- Conversational interface built with Amazon Lex
- Serverless backend using AWS Lambda
- Query execution on AWS RDS and Amazon Athena
- Modular intent handling for healthcare-related domains

---

## 🧠 Supported Use Cases
The chatbot supports predefined healthcare-focused intents, including:
- **Health Insurance Providers**
- **Hospital Patient Satisfaction**
- **Patient Diagnosis**
- **Treatment Categories**

Each intent triggers backend logic that translates user
