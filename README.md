# 🧠 Sprint Watchdog

A Python automation toolkit to track sprint health, slipping stories, backlog status, and team readiness in Jira — with Slack integration for proactive notifications.

## 🔧 Features

- 📊 Sprint Readiness Report
- 🧹 Backlog Health Analyzer
- 🐢 Slipping Story Tracker
- 🤖 Slack Bot Notifications via `Sprint Watchdog`
- 🧪 Uses `.env` file for secure token loading

## 📦 Requirements

- Python 3.8+
- A `.env` file (not tracked) with:

```env
SLACK_BOT_TOKEN=your-slack-token-here
JIRA_API_TOKEN=your-jira-api-token-here
