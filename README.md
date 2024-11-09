# automated_email_sender

Automated Email Replier with Gorg, DuckDuckGo Search, and CrewAI
This project integrates Gorg, DuckDuckGo Search, and CrewAI to create an automated email replier system. The system is capable of processing incoming emails, searching for relevant information using DuckDuckGo, and generating responses based on the gathered information. CrewAI is used for orchestrating the tasks involved in processing and replying to emails.

Project Overview
The Automated Email Replier uses Gorg for advanced knowledge extraction, DuckDuckGo Search to gather relevant information from the web, and CrewAI for orchestrating the workflow of tasks. This enables the system to not only reply to emails but also research the necessary context before crafting the response.

Key Features
Email Content Analysis: The system reads incoming emails and identifies key topics or questions.
Web Search Integration: Utilizes DuckDuckGo to search for relevant information and enhance the email reply.
Automated Email Response Generation: Automatically generates and sends email responses based on the gathered information.
Task Orchestration: Uses CrewAI to manage multiple agents and tasks to perform email processing efficiently.
Libraries Used
Gorg: A tool for knowledge extraction, used to pull relevant data and context.
DuckDuckGo Search: A search engine to fetch relevant information from the web.
CrewAI: A framework for managing agents and orchestrating tasks.
smtplib: For sending emails through SMTP.
email: A library for parsing and composing email messages.
