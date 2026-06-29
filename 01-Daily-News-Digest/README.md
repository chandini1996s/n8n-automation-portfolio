# 📰 Automated Daily News Digest using n8n

## Project Overview

This workflow automatically retrieves the latest news headlines from NewsAPI and sends the top 10 headlines via Gmail every day.

## Workflow

Schedule Trigger

↓

HTTP Request (NewsAPI)

↓

Split Out

↓

Limit (Top 10)

↓

Code Node

↓

Gmail

## Features

* Automatic scheduling
* API integration
* JSON processing
* JavaScript formatting
* Gmail automation

## Technologies

* n8n
* JavaScript
* REST API
* Gmail
* JSON

## Future Improvements

* AI summarization
* Category filtering
* Telegram notifications
* Google Sheets logging
