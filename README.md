# Voice-Directed Task Management System

> **Call to check any task status. Delegate without dashboards, pinging, or typing.**

A voice-first automation system that connects Voiceflow, n8n, Notion, Slack, Gmail, and Twilio to enable natural conversation about tasks and automatic instruction delivery to your team.

## What This Is

This repository contains the complete implementation of a voice-directed task management prototype that allows you to:

- **Call and ask about any task** - "What's the status of the client training for Bloom Events?"
- **Give follow-up instructions** - "Tell Alex to prioritize this task"
- **Automatic team communication** - Instructions formatted and sent via Slack
- **Complete audit trail** - Everything logged to Gmail

## Repository Contents

### n8n Workflows
- `StatusLookup_core.json` - Main workflow handling task lookup and instruction routing
- `StatusLookup_add.json` - Task creation workflow
- `StatusLookup_update.json` - Task update workflow
- `StatusLookup_archive.json` - Task archiving workflow

### Voiceflow Agent
- `StatusLookup-2025-07-13_12-41.vf` - Complete conversational AI configuration with dual agents

## How It Works

**One Call. Six Tools. Aligned Action.**

1. **Twilio** captures your call
2. **Voiceflow** interprets your task inquiry or instruction
3. **n8n** searches your Notion database and routes responses
4. **Notion** provides task data
5. **Slack** delivers formatted instructions to team members
6. **Gmail** creates documentation trail

The system uses intent detection to automatically route between task lookup and instruction delivery in a single conversation flow.

## The Result

- Faster decisions
- Fewer miscommunications  
- Cleaner operations
- Less chasing, more leading

## Demo

Try the chat version: [harmony.neurvana.ai/task-manager](https://harmony.neurvana.ai/task-manager/)

## Contact

**Luke McNeur**  
lukemc@neurvana.ai  
https://Neurvana.AI  
212 287 9353

---

*Skip the apps. Talk and execute.*
