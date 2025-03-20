# 𝐆𝐞𝐧𝐀𝐈-𝐏𝐨𝐰𝐞𝐫𝐞𝐝 𝐌𝐮𝐥𝐭𝐢𝐦𝐨𝐝𝐚𝐥 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 & 𝐋𝐋𝐌-𝐃𝐫𝐢𝐯𝐞𝐧 𝐘𝐨𝐮𝐓𝐮𝐛𝐞 𝐈𝐧𝐭𝐞𝐥𝐥𝐢𝐠𝐞𝐧𝐜𝐞 

## **Introduction**  
This project leverages **Generative AI, Large Language Models (LLMs), and NLP** to extract **insights, summaries, and sentiment analysis from YouTube videos**. By integrating **Google Gemini API, OpenAI GPT, and multimodal AI processing**, this tool transforms raw video data into structured, meaningful insights for businesses, researchers, and content creators.  

## **Project Objective**  
The goal is to **automate** the **extraction, processing, and analysis** of YouTube video content using advanced AI. This tool provides **summarization, sentiment analysis, metadata extraction, and predictive insights**, helping users understand audience engagement and video sentiment efficiently.  

## Key Highlights
**Multimodal AI Analysis** → Uses **Google Gemini AI & OpenAI GPT** to analyze **text, metadata, and sentiment**  
**Generative AI-Powered Summarization** → Leverages **BART (facebook/bart-large-cnn)** for concise **video summaries**  
**Sentiment Analysis with Deep Learning** → Uses **RoBERTa (cardiffnlp/twitter-roberta-base-sentiment)** for **audience sentiment classification**  
**Metadata Extraction** → Fetches **title, description, tags, and engagement metrics** via **YouTube Data API**  
**Automated PDF Generation** → Saves **transcripts as PDFs** using **FPDF**  
**Scalable API & Deployment** → Implements **FastAPI & ngrok** for **real-time API access**  

---

## **Technologies Used**  

### **Generative AI & LLMs**  
- **Google Gemini AI (Gemini 1.5 Pro)** → AI-powered interpretation of YouTube transcripts & metadata  
- **OpenAI GPT API** → Deep content summarization & semantic analysis  

### **NLP & Transformers**  
- **BART (facebook/bart-large-cnn)** → Transformer-based AI summarization  
- **RoBERTa (cardiffnlp/twitter-roberta-base-sentiment)** → Sentiment analysis for video transcripts  

### **API Integrations & Automation**  
- **YouTube Transcript API** → Fetching subtitles  
- **YouTube Data API** → Extracting video metadata  
- **FastAPI + Async Processing** → Scalable API architecture  
- **ngrok Deployment** → Public API access  

### ** AI-Powered Video Analytics**  
- **Sentiment Breakdown** → Positive, Negative, Neutral classification  
- **AI-Generated Summaries** → Key takeaways from video content  
- **Google Gemini AI Interpretations** → Deep content intelligence  

### **Automated Documentation & Reporting**  
- **FPDF** → Generates PDF transcripts for offline use  

### **Optimized Performance**  
- **FastAPI & asyncio** → Asynchronous processing for speed  
- **Parallel Processing** → Efficiently handling large transcript chunks  
- **ngrok Deployment** → Exposing APIs in real time  

---

## ** Challenges Faced & Solutions**  

1**YouTube Restrictions on Audio/Video Downloading**  
- **Challenge:** YouTube policies block direct downloads, limiting transcription options.  
- **Solution:** Used **YouTube Transcript API** for subtitles and planned **Whisper AI** for videos without captions.  

2 **Handling Large Transcripts with API Limits**  
- **Challenge:** **Google Gemini AI & BART** have token limits, complicating long transcript processing.  
- **Solution:** Implemented **text chunking** to split transcripts for smooth summarization & sentiment analysis.  

3 **API Running Time Constraints**  
- **Challenge:** LLMs and sentiment models faced **execution time limits**, causing failures.  
- **Solution:** Used **FastAPI with asyncio** for efficient, scalable task processing.  

4**Ensuring High-Performance API Processing**  
- **Challenge:** Large video data slowed down processing with multiple AI models.  
- **Solution:** **Optimized with parallel processing, batched API calls, and ngrok** for real-time API access.  

5 **Deploying the API for Public Access**  
- **Challenge:** Hosting without a dedicated cloud server was tricky.  
- **Solution:** Used **ngrok** to expose the FastAPI service, allowing **public access without full cloud deployment**.  

---

## ** Future Enhancements**  

**Multimodal AI Expansion** → Integrate **Whisper AI** for speech-to-text & **CLIP AI** for video analysis  
**Real-Time YouTube Analysis** → Process **live-streamed videos**, providing **real-time sentiment tracking & alerts**  
**Multilingual Support** → Translate transcripts via **Google Translate API** & analyze sentiment across languages  
**Predictive Video Analytics** → Forecast **engagement trends (views, likes, shares)** & detect **viral content**  
**Conversational AI for Video Insights** → Develop a **chatbot powered by GPT/Gemini** to provide **instant insights**  
**Personalized AI Summaries & Video Highlights** → Generate **custom summaries & AI-driven highlight reels**  
**Interactive Dashboard & API** → Build a **dashboard** to track video trends, insights & sentiment analysis  

---

## **Report & Code**  
**Full Analysis Report** → `"AI-Driven-YouTube-Analysis-Report.pdf"`  
**Code & Implementation** → `"AI-YouTube-Analysis.ipynb"`  

---

**👤 Author & Contact**  
**Pramod Mantya Raju**  
**Data Scientist | AI & ML Engineer | Product Manager**  
MSBA & MBA | Python, SQL, & Analytics | **Ex-Philips | Ex-CGI**  
📩 **LinkedIn**: [Your LinkedIn Profile]  


