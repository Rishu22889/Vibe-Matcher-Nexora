# 🎽 Vibe Matcher — AI Recommender Prototype  
**Author:** Risu Raj (IIT ISM Dhanbad)  
**For:** Nexora AI Internship Task — November 2025  

## 🧠 Overview  
A mini recommender that takes a vibe query like “energetic urban chic” and finds the top-3 matching fashion items using semantic embeddings (SentenceTransformers) and cosine similarity.  

## ⚙️ Workflow  
1. Create dataset of 10 mock fashion items with vibe tags.  
2. Generate embeddings with `all-MiniLM-L6-v2`.  
3. Query embedding + cosine similarity → top-3 matches.  
4. Evaluate latency and similarity thresholds.  

## 📈 Example Output  
Query: warm and cozy knitwear for evenings
Top Match: Cozy Knit Sweater (score=0.813)


## 🧩 Reflection  
- Next step: Pinecone/FAISS integration for large-scale vector search.  
- CLIP-based multimodal matching (image + text).  
- Low-similarity fallback for user-friendly UX.  
- Latency under 0.02s per query — ideal for real-time recommendations.  

## 🌟 Why AI at Nexora  
AI at Nexora excites me because it transforms creativity into measurable impact. This project strengthened my belief that human-centered ML systems can enhance personalization and design intelligence.
