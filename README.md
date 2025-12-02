# AI-Powered Personal Branding Website + Chat Assistant

This project is an interactive personal branding website combined with a no-code AI assistant.  
The website (built with Carrd) is enhanced with a Tiledesk chatbot powered by OpenAI models, a structured Knowledge Base, and a minimal system prompt.

The goal is to create an engaging, recruiter-friendly experience where visitors can ask questions about my background, skills, AI journey, and contact details.

---

## Features

- One-page personal website (Carrd)
- Embedded Tiledesk chat widget
- AI welcome message
- Knowledge Base (30 structured entries)
- Ultra-light system prompt
- GPT-4.1 mini / GPT-4o mini for optimized cost
- Custom no-code flow (welcome → KB query → reply)
- Fallback handling for unrelated questions
- Minimal token usage (55 max tokens)
- Professional and warm assistant tone

---

## System Prompt

Warm, clear assistant representing Katarzyn. Subtle PR, no overclaiming.

---

## Architecture

1. User visits aiwithkatarzyn.com
2. Chat widget loads
3. AI Welcome Block triggers
4. User sends question
5. Tiledesk retrieves relevant KB chunks
6. OpenAI model generates answer using system prompt
7. Fallback reply for out-of-scope topics

---

### Dual AI Layer Architecture
Tiledesk separates Knowledge Retrieval (KB engine) from Conversational Reasoning (flow engine).  
Each layer has its own system prompt and temperature, allowing the assistant to retrieve information flexibly while keeping a consistent personality and voice in user-facing responses.

---

## Technologies Used

- Carrd
- Tiledesk (AI blocks, flows, KB)
- OpenAI GPT-4.1 mini / 4o mini
- No-code logic and prompt engineering
- Token and chunk optimization

---

## Demo

**https://aiwithkatarzyn.com**

---

## Future Improvements

- Multi-language support  
- Skills recommendation module
- Portfolio previews inside the chat  


