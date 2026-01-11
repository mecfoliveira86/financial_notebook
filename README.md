# Preparing the ground to the financial fruits

> **A project developed for the DIO & Bradesco Bootcamp: "Data Science with Generative AI."**
> 
> **Access the Live Notebook:** [NotebookLM - InvestEdu-BR](https://notebooklm.google.com/notebook/98d61595-de93-4e7e-8bb2-d509308db896)

---

## 📌 Project Context
This repository was born from a challenge driven by **DIO (Digital Innovation One)** and **Bradesco**. These organizations aim to spread Data Science and AI methodologies by teaching students how to leverage tools like **NotebookLM** for active learning.

### The Challenge
The original goal was:
> "The challenge proposes the creation of a thematic notebook in NotebookLM, gathering three to five open sources in text or PDF on an introductory financial subject. From this material, study objectives are defined, strategic questions are developed, and prompt variations are tested, recording the responses and their references. The expected result is a study mini-guide with structured summaries, a glossary of concepts, and a set of reusable prompts that support future reviews."

---

## 📂 Data Sources & Reliability
To ensure the information provided by the AI is accurate, legal, and impartial, all sources used in this Notebook were retrieved from:

* **[Portal do Investidor - Publicações Educacionais](https://www.investidor.gov.br/portaldoinvestidor/export/sites/portaldoinvestidor/menu/Menu_Investidor/publicacoes/Publicacoes_Educacionais.html)**
* **Provider:** Brazilian Securities and Exchange Commission (**CVM - Comissão de Valores Mobiliários**).
* **Reliability:** These are official government documents designed to provide unbiased financial education to the Brazilian public.

---

## 🧠 Methodology & Prompt Engineering
Since I am not a financial specialist, I used a **progressive prompt engineering strategy** with Gemini AI to build this knowledge base from the ground up.

### Stage 1: Establishing the Foundation (Beginner's Perspective)
The first step was to identify the "pillars" of finance to ensure the notebook would be relevant for absolute beginners.
* **Prompt:** *"I would like to understand more about finance. I know nothing about the subject. I need an introductory guide to start investing. What are the 5 basic subjects I need to know to start this journey?"*
* **Goal:** Map out the necessary knowledge and create a beginner-friendly environment.

### Stage 2: Source Curation & RAG Preparation
I used Gemini to filter the best documents from the official Portal do Investidor.
* **Prompt:** *"Help me locate open-source text or PDF documents about each of these introductory financial topics... Deliver a table with the subjects, document titles, and access links."*
* **Goal:** Efficiently curate the knowledge base (Grounding) that powers the AI's responses with reliable official data.

### Stage 3: UX & Navigation (The Master Prompt)
I implemented a "Master Prompt" that functions as a homepage menu for the user.
* **Prompt:** *"Help me create a 'Master Prompt' for NotebookLM. It needs to use a communication style for beginners. If possible, insert a menu (Knowledge Tree) so the user sees the main content every time they access it."*
* **Goal:** Enhance user experience (UX) and provide a clear roadmap within the platform.

### Stage 4: Scenario Simulation & Goal Planning
The final layer was adding functional logic so users could simulate their own financial dreams.
* **Prompt:** *"I want this notebook to help people achieve their financial goals when they indicate values and deadlines... Suggest a note that allows for scenario simulations within the notebook."*
* **Goal:** Move from passive reading to active financial planning.

---

## 🛠 Features
* **Knowledge Tree:** A structured menu for easy navigation.
* **Legal Compliance:** Strictly based on CVM educational guidelines.
* **Interactive Simulations:** Tools to calculate time and capital needed for financial goals.
* **Glossary:** Auto-generated definitions for complex terms like Selic, IPCA, and CDI.

## 🚀 How to Use
1.  Open the [NotebookLM link](https://notebooklm.google.com/notebook/98d61595-de93-4e7e-8bb2-d509308db896).
2.  Review the **"Master Guide"** pinned in the notes.
3.  Utilize the chat to interact with the sources. **Example query:** *"Based on the CVM documents, what are the first steps to start investing in Renda Fixa?"*

---

## 👨‍💻 Author
Developed as part of a professional portfolio to demonstrate expertise in **Generative AI, Prompt Engineering, and Specialized Data Curation.**
