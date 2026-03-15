# Ai_study_assistant_agent
AI-Powered Study assistant using Telegram, Groq LLM API, and Workflow Automation and LLM Integration.

This project integrates Telegram messaging, AI API Responses, and automated reminder scheduling using workflow orchestration.

-----------
#Features

* AI-Powered question answering
* Study reinder automation
* Google Calender event creation
* Telegram chatbot interface
* workflow-based autoamtin logic

------------
##Workflow Architecture

User interacts with a Telegram bot which triggres the workflow

The system detect user intent:

If reminder requesy -> Send reminder message and create Google Calendar event.

If general question -> Send request to AI API and return response

--------------
##Technologies Used

-n8n workflow Automation
-Telegram Bot API
-Groq LLM API
-Google Calendar API

-----------------
##Screenshot

###Workflow Architecture
![Workflow](screenshots/workflow-architecture.png)

###Telegram Bot
![Telegram](screenshots/telegram-chat.png)

###Reminder Event 
![Calendar](screenshots/calendar-reminder.png)

-----------------

##Future Improvements

*Multi-user reminder support
*Daily learning summary agent
*User learning history tracking
*Web search integration




