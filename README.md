# WhatsApp Automation Workflow using n8n

This repository contains an `n8n` workflow to automate WhatsApp interactions using Twilio.

## Features
- Commands: LIST, DELETE, MOVE, SUMMARY
- Command parsing & validation
- Integration with Google Drive

## Setup
1. Import `workflow.json` in n8n.
2. Set environment variables for Google , Twilio , OpenAI credentials.
3. Deploy using Docker (see `docker-compose.yml`).

## Deployment

```bash
docker compose up -d
