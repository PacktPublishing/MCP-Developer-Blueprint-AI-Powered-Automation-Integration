# Twitter MCP Tool

This repository contains the **Twitter MCP Tool**, a tool designed to streamline social media tasks using Python. It includes features for tweeting, username change history and, Fetch recent tweets.

## Features

### 1. **Tweet Posting**
Post tweets directly to Twitter.  

### 2. **Tweet with LLM**
Post tweets directly to Twitter with the help of LLM. 

### 3. **Query Username Changes**
Track the username change history of any Twitter account.

### 4. **Fetch Recent Tweets**
Retrieve the latest tweets from any public Twitter user's timeline.  


## Prerequisits

1. X API Key Secrets [Generate from here](https://developer.x.com/)

2. Gemini API Key Setup [Generate from here](https://ai.google.dev/gemini-api/docs/api-key)

3. Claude Desktop [Download from here](https://claude.ai/download)

## Installation

1. Change the working directory
     ```bash
     cd 06_twitter_server
     ```

2. Install dependencies:
     ```bash
     uv venv
     .venv\Scripts\activate
     uv pip install -r requirements.txt
     mcp dev main.py
     ```
     And if you want to install it in the claude desktop then use 
     ```bash
     mcp install main.py
     ```

3. Create a `.env` file with the following keys:
     ```env
     X_api_key=<your_twitter_api_key>
     X_api_key_sec=<your_twitter_api_secret>
     X_access_token=<your_twitter_access_token>
     X_access_token_sec=<your_twitter_access_token_secret>
     X_bearer_token=<your_twitter_bearer_token>
     GEMINI_API_KEY=<your_genai_api_key>
     ```

## Usage 

Open your claude desktop you will see the Twitter MCP Tool is ready to use.

If not then Copy paste the `config.json` into your claude_desktop_config.json

And set your projects PATH instead of D:\\MCPServers\\edquest-mcp\\mcp_e2e\\06_twitter_server

## Folder Structure
```
.
├── main.py             # MCP core logic
├── .env                # Environment variables
├── requirements.txt    # Python dependencies
├── config.json         # config file for claude desktop
└── readme.md           # Project documentation
```
