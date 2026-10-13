# 💬 Digital Financial Literacy AI Agent

An AI-powered assistant designed to help users understand and navigate digital finance safely. Built using IBM Watsonx.ai and Retrieval-Augmented Generation (RAG), this intelligent agent provides multilingual support and trustworthy guidance on UPI, interest rates, stock market, personal finance, investing , loan safety, fraud prevention, online scams and more.

## 👩‍🎓 Project Details

- **Name:** Lingamsetti Dhana Pavitra
- **Institution:** ISTS Women’s Engineering College
- **Project:** Digital Financial Literacy AI Agent

## 🧩 Problem Statement

Many individuals, especially from rural or digitally underserved areas, lack financial literacy. They struggle with understanding UPI, online scams, interest rates, or personal budgeting. This can lead to fraud, poor money management, or digital exclusion.


## 💡 Proposed Solution

An AI agent trained using IBM Watsonx.ai that delivers reliable, document-based answers about digital finance. With multilingual support and document retrieval (RAG), it ensures users receive grounded, easy-to-understand financial guidance.


## 🧠 Technologies Used

- IBM Watsonx.ai Studio
- IBM Granite Foundation Model (LLM)
- IBM Watson Discovery for document indexing, search, and retrieval (RAG; managed retrieval service, not a standalone vector database)
- PDF documents from RBI/NPCI & other related sourses
- NLP (Natural Language Processing)
- IBM Cloud Object Storage

## ☁️ IBM Cloud Services Used

- Watsonx.ai Studio
- IBM Granite Model
- IBM Watson Discovery
- IBM Cloud Lite Account
- IBM Cloud IAM
- IBM Cloud Object Storage

## 👥 End Users

- General public seeking financial clarity  
- Rural and semi-urban citizens  
- Students and young professionals  
- First-time UPI and digital banking users  
- NGOs and government outreach programs  
- Customer service centers
- Self-Help Groups / Women’s Collectives
- Educators / Institutions

## 🌟 WOW Factors

- Uses RAG to fetch answers from real RBI/NPCI or uploaded PDFs  
- Built entirely on IBM Cloud using Watsonx tools  
- Handles unrelated questions with polite redirection  
- Future-ready with multilingual support  
- Educates users on scams, interest rates, budgeting, stock market, UPI, and more  
- Provides safe and personalized financial guidance

## 🧪 Key Features

- Document-based Q&A via Vector Index(IBM watson discovery)  
- Powered by IBM Granite LLM for natural language understanding  
- Built-in NLP support  
- Responds gracefully to off-topic/irrelated questions  
- Covers real financial concerns (scams, loans, savings, UPI, etc.)

## 🚀 How It Works

1. User inputs a query (e.g., “How to avoid UPI fraud?”)
2. IBM Granite LLM processes the language
3. IBM Watson Discovery retrieves relevant passages from indexed financial documents
4. Agent responds with a grounded, natural-language answer

## 📌 How to Run or Deploy

1. Log in to IBM Cloud Lite: https://cloud.ibm.com
2. Launch Watsonx.ai Studio
3. Create a new AI Agent
4. Create an IBM Watson Discovery project and ingest trusted financial-literacy documents (for example, official RBI and NPCI material).
5. Set these environment variables in the notebook runtime: 
WATSON_DISCOVERY_URL
 WATSON_DISCOVERY_APIKEY 
 WATSON_DISCOVERY_PROJECT_ID
6. Set `PROJECT_ID` or `SPACE_ID` and provide the watsonx.ai API key as prompted.
7. Run the notebook cells and test questions about UPI safety, online banking, and fraud prevention. The agent calls Watson Discovery and uses returned passages as context.
8. Verify that the indexed documents and retrieval results are relevant before relying on answers. Deploy through a web UI only after end-to-end testing.

## 🛣️ Future Scope

- WhatsApp or mobile app integration  
- Speech-to-text input for voice-driven queries  
- Automatic monthly report generation  
- Region-specific financial policy updates  
- Multilingual expansion with Watson Language Translator


> Created with 💙 during the IBM SkillsBuild for Academia Internship 2025 by **LINGAMSETTI DHANA PAVITRA**
