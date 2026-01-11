# InvestEdu-BR: Financial Literacy via Prompt Engineering

> **A project developed for the DIO & Bradesco Bootcamp: "Data Science with Generative AI."**
> 
> **Access the Live Notebook:** [NotebookLM - InvestEdu-BR](https://notebooklm.google.com/notebook/98d61595-de93-4e7e-8bb2-d509308db896)

---

## 📌 Project Context
This repository was born from a challenge driven by **DIO (Digital Innovation One)** and **Bradesco**. These organizations aim to spread Data Science and AI methodologies by teaching students how to leverage tools like **NotebookLM** for active learning.

### The Challenge
The original goal was:
> "The challenge proposes the creation of a thematic notebook in NotebookLM, gathering three to five open sources in text or PDF on an introductory financial subject. From this material, study objectives are defined, strategic questions are developed, and prompt variations are tested, recording the responses and their references. The expected result is a study mini-guide with structured summaries, a glossary of concepts, and a set of reusable prompts that support future reviews. The activity emphasizes the use of AI as an active learning tool, combining critical thinking, source curation, and knowledge organization."

---

## 🧠 Methodology & Prompt Engineering
Since I am not a financial specialist, I used a **progressive prompt engineering strategy** with Gemini AI to build this knowledge base from the ground up, ensuring impartial and high-quality information.

### Stage 1: Establishing the Foundation (Beginner's Perspective)
The first step was to identify the "pillars" of finance to ensure the notebook would be relevant for absolute beginners.
* **Prompt:** *"I would like to understand more about finance. I know nothing about the subject. I need an introductory guide to start investing. What are the 5 basic subjects I need to know to start this journey?"*
* **Goal:** Create a scenario-based environment adjusted for beginners to map out the necessary knowledge.

### Stage 2: Source Curation & RAG Preparation
To feed the NotebookLM, I needed high-quality, open-source data. 
* **Prompt:** *"Help me locate open-source text or PDF documents about each of these introductory financial topics... Deliver a table with the subjects, document titles, and access links."*
* **Goal:** Efficiently curate the knowledge base (Grounding) that powers the AI's responses with reliable data.

### Stage 3: UX & Navigation (The Master Prompt)
To improve usability, I implemented a "Master Prompt" that functions as a homepage menu whenever a user accesses the notebook.
* **Prompt:** *"Help me create a 'Master Prompt' for NotebookLM. It needs to use a communication style for beginners. If possible, insert a menu (Knowledge Tree) so the user sees the main content every time they access it."*
* **Goal:** Enhance user experience (UX) and provide a clear roadmap for the student within the platform.

### Stage 4: Scenario Simulation & Goal Planning
The final layer was adding functional logic so users could simulate their own financial dreams.
* **Prompt:** *"I want this notebook to help people achieve their financial goals when they indicate values and deadlines... Suggest a note that allows for scenario simulations within the notebook."*
* **Goal:** Move from passive reading to active financial planning, helping users focus on the tools needed to achieve specific dreams while saving time.

---

## 🛠 Features
* **Knowledge Tree:** A structured menu for easy navigation.
* **Legal Compliance:** Focus on education and legal pathways within the Brazilian market (CVM standards).
* **Interactive Simulations:** Tools to calculate time and capital needed for financial goals.
* **Glossary:** Auto-generated definitions for complex Brazilian economic terms (Selic, IPCA, CDI).

## 🚀 How to Use
1.  Open the [NotebookLM link](https://notebooklm.google.com/notebook/98d61595-de93-4e7e-8bb2-d509308db896).
2.  Review the **"Master Guide"** pinned in the notes.
3.  Utilize the chat to interact with the sources. **Example query:** *"I want to save R$ 10.000 in 2 years. Based on the sources, what are the best legal ways to start?"*

---

## 👨‍💻 Author
Developed as part of a professional portfolio to demonstrate expertise in **Generative AI, Prompt Engineering, and Data Curation.**
