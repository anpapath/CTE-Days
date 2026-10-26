# 🤖 How Does AI Actually Work?
A hands-on session on how large language models work: see how ChatGPT-style AIs process text, build your own RAG system and try to break it, then send an AI agent to investigate a data leak.

## 🚀 Start here
Click **Open in Colab** next to a notebook and sign in with your Google account. Then click **File → Save a copy in Drive** so you have your own version to work in.

| | Notebook | Open | What you'll do |
|---|---|---|---|
| 🧠 | [Lecture demos](notebooks/00_Lecture_Demos.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anpapath/CTE-Days/blob/main/notebooks/00_Lecture_Demos.ipynb) | The live demos from the lecture: tokens, embeddings and cosine similarity, attention, and how a model predicts the next word |
| 📚 | [Lab 1: AI Librarian](notebooks/01_Lab_RAG_AI_Librarian.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anpapath/CTE-Days/blob/main/notebooks/01_Lab_RAG_AI_Librarian.ipynb) | Pick a theme (Music, Film, Space or Cybersecurity), build an AI that answers from your own documents (RAG), then red-team it with poisoned documents and prompt injection |
| 🕵️ | [Lab 2: Detective Bot](notebooks/02_Lab_Agent_Detective.ipynb) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/anpapath/CTE-Days/blob/main/notebooks/02_Lab_Agent_Detective.ipynb) | Give an AI agent tools through function calling and watch it solve "The Case of the Leaked Prototype" on its own, then try to hijack it |

## 📖 What's inside
- `notebooks/`: the Colab notebooks
- `knowledge_base/`: the documents the AI librarian in Lab 1 reads, one folder per theme, plus a made-up company handbook (Quokka Robotics) and hackathon rulebook (NeonHack 2026) that no AI could know about. Lab 1 already has them built in, so you don't need to upload anything.

## 🧭 How to use a notebook
- Press **Shift + Enter** to run a cell, going from top to bottom.
- Cells marked ✏️ are for you to change. Edit them and run them again.
- Cells with a title hide their code. Double-click one to read it: it's all plain Python.
- Labs 1 and 2 ask for an **API key** at the start. Your teacher will give it to you during the session.
- Something broken? **Runtime → Restart and run all**.

## 🛡️ Using AI like a professional
- AI can sound confident and still be wrong. Verify facts, and open any source it cites.
- Never paste passwords, personal data or confidential files into a public chatbot.
- Follow your school's or university's rules on AI, and say when you used it.
- Use AI to learn faster, not to skip the thinking.

---
*Names of real artists, films and franchises (including Harry Potter and Star Wars) are used for educational purposes only. All trademarks belong to their owners, and this project is not affiliated with them. Quokka Robotics, NeonHack 2026 and everyone in the Lab 2 case are fictional.*
