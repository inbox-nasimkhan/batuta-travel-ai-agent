# AI-Powered Travel Support Bot 🧳🤖

A practical automation case study — an AI Agent built for a Bangladeshi travel agency to handle customer support directly on Telegram.

## What it does

Customers message the agency's Telegram bot with everyday questions — tour packages, visa requirements, pricing, office hours, custom bookings — and the AI Agent answers instantly, using the agency's own business rules and information.

## Stack

- **Telegram** — customer-facing channel
- **n8n** — no-code workflow automation
- **AI Agent (n8n)** — understands the question and decides how to respond
- **Groq** — LLM inference for fast responses

## Workflow

Telegram Trigger → AI Agent → Groq Chat Model → Telegram Reply

## Example use cases

- "What tour packages do you have for Cox's Bazar?"
- "What documents do I need for a Thailand visa?"
- "What are your office hours?"
- "How much would a trip to Thailand cost?"

## Status

This was built as a prototype / case study project while learning no-code AI automation. The original n8n environment is currently offline (free-tier trial expired), but the workflow design and learnings remain documented here.

## What I learned

- AI automation isn't just about the tools — it's about understanding the business well enough to know what to automate
- A clear, structured prompt (Role + Context + Business Rules) makes the agent far more accurate
- Understanding the business comes before building the automation

## About me

I'm learning AI automation (n8n, no-code) and building practical projects like this one. Open to freelance work — reach out if you think I could help automate something in your business.

**LinkedIn:** [https://www.linkedin.com/in/golam-mursalin-khan-nasim-bb1048429?utm_source=share_via&utm_content=profile&utm_medium=member_android]