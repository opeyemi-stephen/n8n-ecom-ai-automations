# n8n E-com AI Automations

This repository contains the n8n workflows I have built for my AI Virtual Assistant portfolio.

## Project 1: AI Customer Support Deflection Bot (RAG)
**Status:** Completed & Tested
**Stack:** n8n, Supabase (Vector DB), Gemini (Embeddings), DeepSeek (LLM).

**Workflows Included:**
1. **Ingestion Workflow:** Fetches FAQ text from a Google Doc, chunks it, embeds it using Gemini, and stores it in a Supabase vector table.
2. **Live Query Workflow:** A webhook-triggered AI Agent that answers customer questions based on the Supabase data.

**Core Features:**
- RAG (Retrieval-Augmented Generation) architecture.
- Secure webhook authentication.
- AI Agent with tool-calling capabilities to search the vector database.

*Note: Credentials and API keys are stripped out of these JSON files for security. You will need to reconnect your own credentials to run them.*
