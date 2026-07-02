
# AI Learning Path Generator

An AI-powered workflow built with **n8n** that generates a personalized day-wise learning plan based on a user's learning goal.

## Features

- Generate personalized learning roadmaps
- AI-powered curriculum generation using Mistral AI
- Find learning resources
- Create a Google Doc with the complete roadmap
- Schedule learning sessions in Google Calendar
- Automated workflow using n8n

## Tech Stack

- n8n
- Mistral AI
- Google Docs API
- Google Calendar API
- MCP Client Tool
- SerpAPI

## Workflow

1. User enters a learning goal.
2. AI generates a day-wise learning plan.
3. Relevant learning resources are collected.
4. A Google Document is created.
5. Calendar events are scheduled automatically.
6. The Google Document link is returned.

## Installation

1. Clone the repository.

```bash
git clone https://github.com/your-username/learning-path-generator.git
```

2. Import the workflow JSON into n8n.

3. Configure the required credentials:
   - Mistral AI API
   - Google Docs
   - Google Calendar
   - SerpAPI

4. Activate the workflow.

## Example Goal

```
Learn LangChain in 30 days
```

## Output

- Personalized learning curriculum
- Google Document
- Google Calendar schedule

## Author

Priti Alapure
