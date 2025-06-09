# PersonaCache - A Specialized Conversational AI Agent

![AI](https://img.shields.io/badge/AI-Conversational-blue)
![Platform](https://img.shields.io/badge/Platform-ElevenLabs-black)
![License](https://img.shields.io/badge/License-MIT-green)

PersonaCache is a proof-of-concept project demonstrating how to build hyper-specialized, voice-first AI assistants that are both reliable and context-aware. This repository showcases its flagship persona: the **"Tamil Nadu Information Guide."**

This agent is designed to be a trustworthy expert on the Indian state of Tamil Nadu, providing accurate information sourced from a curated knowledge base.

---

## 🚀 Live Demo

You can interact with the "Tamil Nadu Information Guide" live on the ElevenLabs platform. Click the link below to start a conversation!

👉 **[Talk to the Agent Here](https://elevenlabs.io/app/talk-to?agent_id=agent_01jxav3a41f9ere3av7kaymjx1)**

---

## 🎥 Demo Video

Watch this video demonstration to see the agent in action and understand its core capabilities.

---

## ✨ Key Features

* **Voice-First Interaction:** Engages users through natural, lifelike spoken conversation.
* **Domain-Specific Expertise:** Exclusively trained on a curated knowledge base about Tamil Nadu, covering tourism, government services, culture, and more.
* **Accuracy-Focused:** Built on a Retrieval-Augmented Generation (RAG) model, which prevents it from making up information.
* **No Hallucinations:** If the answer is not in its knowledge base, the agent will say so, ensuring high reliability.
* **Extensible Framework:** Designed as a "PersonaCache," allowing for future "personas" (e.g., a real estate agent, a product advisor) to be added.

---

## 🤔 The Problem It Solves

Generic AI models, while powerful, often struggle with specific, local context and can provide inaccurate or "hallucinated" answers. PersonaCache aims to solve this by creating trustworthy "digital experts" that provide verified information for a specific domain, building user trust and delivering real value.

---

## 🛠️ Technology Stack

* **Conversational AI Platform:** [**ElevenLabs**](https://elevenlabs.io/) - Used for agent creation, lifelike voice synthesis (Text-to-Speech), and hosting.
* **Core Architecture:** Retrieval-Augmented Generation (RAG). The agent retrieves information from a secure, pre-defined knowledge base before formulating an answer.
* **Knowledge Base:** A curated list of authoritative URLs related to Tamil Nadu.

---

## 💡 The "PersonaCache" Concept

PersonaCache isn't just one agent; it's a framework for creating multiple, distinct AI personalities. The "Tamil Nadu Information Guide" is the first implementation. The vision is to expand the "cache" with other personas, such as:
* A hyper-local city concierge.
* A product expert for a niche e-commerce store.
* A 24/7 lead qualifier for a specific industry.

---

## ⚙️ How It Works

The agent follows a simple yet powerful process:
1.  **Listen:** The user asks a question via voice or text.
2.  **Retrieve:** The agent searches its curated knowledge base for relevant information. It does **not** search the open web.
3.  **Synthesize:** It formulates an answer based *only* on the information it found.
4.  **Respond:** It delivers the answer using a natural, lifelike voice. If no information was found, it politely informs the user.

---

##  licenc

This project is licensed under the MIT License - see the `LICENSE` file for details.

## 🙏 Acknowledgments

This project was made possible by the powerful and intuitive tools provided by **ElevenLabs**.
