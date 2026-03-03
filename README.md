# LiveLab 10 – Building an AI Recommendation Engine

## Overview
This instructor demo supports LiveLab 10 and prepares students for the L'Oréal Chatbot Project.

Students will:
- Capture user input
- Send it to an AI endpoint
- Handle API responses
- Implement error handling
- Display dynamic AI recommendations

This demo uses a GlowGuide-inspired UI and integrates with a Cloudflare Worker to securely communicate with the OpenAI API.

---

## File Structure

- index.html → Main structure
- styles.css → Glow-inspired styling
- script.js → API logic + error handling

---

## Setup Instructions (Instructor)

### 1. Fork and Open GitHub Codespaces

### 2. Connect to Your Cloudflare Worker
In `script.js`, replace:

```
YOUR_CLOUDFLARE_WORKER_URL
```

With your deployed Worker endpoint.

Example:

```
https://your-worker-name.your-subdomain.workers.dev
```

---

## Demo Flow During LiveLab

1. Walk through HTML structure.
2. Add styling (discuss visual hierarchy).
3. Add DOM selection in JavaScript.
4. Add event listener.
5. Add fetch request.
6. Add error handling with try/catch.
7. Discuss why API keys must never be exposed.

---

## Teaching Emphasis

### Advanced API Concepts
- POST requests
- JSON body structure
- Handling non-200 responses
- Parsing JSON safely

### Error Handling
- try/catch
- Checking `res.ok`
- Friendly fallback messages
- Console debugging

---

## Connection to L'Oréal Project
This demo directly prepares students to:
- Build a branded chatbot
- Route requests securely through Cloudflare Workers
- Integrate OpenAI
- Handle errors professionally
- Prepare for conversation UI enhancements

---

## Optional Extensions
- Add loading animation
- Maintain conversation history
- Style chat bubbles
- Deploy to production

---

© 2026 Educational Demo – LiveLab 10
