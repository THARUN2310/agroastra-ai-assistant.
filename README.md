# AgroAstra – AI Agricultural Assistant

## Overview
AgroAstra is an AI-powered agricultural advisory system that helps farmers receive real-time guidance via messaging platforms such as WhatsApp, Telegram, and SMS.

## Features
- Multilingual farmer assistance
- Weather-based crop alerts
- Crop disease advisory
- Market price insights
- Government scheme recommendations

## Technology Stack
- n8n workflow automation
- WhatsApp Cloud API
- Telegram Bot API
- Twilio SMS
- LLM-based AI advisory
- Weather & market APIs
- Airtable database

## Architecture
![Architecture](architecture/system-architecture.png)

## How It Works
1. Farmer sends message via WhatsApp
2. Webhook triggers n8n workflow
3. AI agent processes query
4. Weather / market APIs provide data
5. Response is sent back to farmer

## Demo
(You can add a video link)

## Future Improvements
- Satellite crop monitoring
- IoT soil sensors
- Predictive crop analytics
