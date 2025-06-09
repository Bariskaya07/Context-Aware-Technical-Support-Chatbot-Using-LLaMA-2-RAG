# Context-Aware-Technical-Support-Chatbot-Using-LLaMA-2-RAG
### 📌 Proje Özeti
Bu proje, LLaMA 2 dil modelini temel alarak ve LangChain kütüphanesini kullanarak bağlama duyarlı ve belge erişimi destekli (retrieval-augmented) bir teknik destek asistanı geliştirmeyi amaçlamaktadır. Hedef, bu sistemin gerçek zamanlı olarak müşteri hizmetleri ve yardım masası (helpdesk) uygulamalarında kullanılabilir olmasıdır.

🧠 Motivasyon
Geleneksel sohbet botları genellikle uzun konuşmaları sürdürememekte veya ilgili belgelere dinamik olarak erişememektedir. Bu proje, bu sınırlamaları aşmak için Retrieval-Augmented Generation (RAG) yöntemini uygulamaktadır. Bu sayede sohbet botunun hafızası güçlendirilmekte ve kaynaklara referans verebilme kabiliyeti kazandırılmaktadır
📌 Overview
This project focuses on developing a context-aware, retrieval-augmented technical support assistant using LLaMA 2 as the base model and LangChain for dynamic document retrieval. It targets real-time applications in helpdesk and customer support environments.

🧠 Motivation
Typical chatbots struggle to handle long conversations or refer to relevant documents dynamically. This project implements Retrieval-Augmented Generation (RAG) to solve this, enhancing the chatbot's memory and citation abilities.

🛠 Planned Features
FAISS vector indexing of product manuals and logs

Context window tuning for coherent multi-turn conversation

Citation-style response generation

Dynamic memory updates across user sessions

🔧 Tech Stack
LLaMA 2 (7B)

LangChain

FAISS for similarity search

Hugging Face Transformers
