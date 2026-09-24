# AI Agent Workflow with n8n and Gemini

This is a simple AI Agent workflow I made using **n8n Cloud** and **Google Gemini 2.5 Flash**.

The nice thing about this agent is that it can do more than just chat. When needed, it can use different tools to **search the web, read websites, and find information online** based on your question.

## Features

* **AI Model:** Uses Google Gemini 2.5 Flash with n8n.
* **Memory:** Uses Simple Memory to remember the conversation and previous messages.
* **Web Tools:** Can search Wikipedia and read content from websites using an HTTP scraper.
* **Chat:** You can use it directly from n8n's built-in chat window.

## How to Setup and Use

You can easily try it on your own n8n:

1. Download the `ai-agent-workflow.json` file from this repo.
2. Open your n8n dashboard and create a new workflow.
3. Click the menu in the top-right and select **Import from File**.
4. Select the JSON file you downloaded.
5. Set up the **Gemini Chat Model** node. You can use n8n Connect or add your own API key.
6. Click **Test Workflow**, open the chat, and start talking to your AI agent.

You can try things like asking the agent to **summarize a website**, search for something online, or find information about a topic.
