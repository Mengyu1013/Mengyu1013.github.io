---
title: "AI-Powered Billing Comparison System for Cloud Cost Optimization"
excerpt: "Designed for DigitalOcean to benchmark AWS invoices, extract services with OCR+LLM, and deliver transparent cloud cost optimization insights. <br/><img src='/images/do-overview.png'>"
collection: portfolio
---

## Motivation
- Cloud invoices (e.g., AWS) often span hundreds of pages, making it difficult for firms to understand their true cost structures.  
- Enterprises require **transparent and interpretable** tools to benchmark cloud service costs and optimize decisions.  
- DigitalOcean, competing with AWS and GCP, aimed to showcase its cost advantage through a **billing comparison feature**.  

---

## Contribution
- 🧠 Designed and implemented an **OCR + LLM-driven billing comparison system**.  
- 🔗 Built a standardized **AWS → DigitalOcean mapping database** to align services and prices.  
- ⚙️ Proposed a **scalable, modular architecture** that supports reusable infrastructure.  
- 📚 Positioned as a **case study in Applied AI for Cloud Economics**, bridging research and practice.  

---

## Method
- **Front-End**: PDF → OCR/LLM extractor → list of AWS services.  
- **Back-End**: Vector embeddings + RAG database → service mapping → output cost comparison.  
- Example: Matching AWS EC2 instances to DigitalOcean Droplets with equivalent compute capacity.  

---

## Results
- Prototype demonstrated **up to 62.9% verified cost savings**, translating to ~$707 annual savings.  
- Enabled transparent, data-driven **decision-making for cloud cost optimization**.  
- Delivered a deployable **Streamlit dashboard** for real-time invoice analysis.  

---

## Screenshots
<img src="/images/do1.jpg" width="650">  
<img src="/images/do2.jpg" width="650">  
<img src="/images/do3.jpg" width="650">  
<img src="/images/do4.jpg" width="650">
