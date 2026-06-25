# 🛒 AI Shopping Agent

> An intelligent shopping assistant powered by **LangChain**, **Groq LLMs**, **Streamlit**, and **SQLite**.

## ✨ Features

🔍 **Natural Language Product Search**
Search products using plain English.

⭐ **Review & Rating Analysis**
Automatically fetches product ratings and review counts.

🖼️ **Image-Based Product Discovery**
Upload a product image and find similar products using a Vision LLM.

🤖 **Agentic Tool Calling**
Uses LangChain tools for search, ratings, image analysis, and checkout.

🛍️ **Smart Ordering Workflow**
Browse → Compare → Confirm → Checkout.

💾 **SQLite Database Integration**
Stores products, reviews, and orders.

---

## 🛠️ Tech Stack

* Python
* LangChain
* Groq (Qwen 3 + Llama 4 Scout Vision)
* Streamlit
* SQLite
* python-dotenv

---

## 📂 Project Structure

```text
.
├── app.py
├── shopping_agent.py
├── reviews_api.py
├── setup_db.py
├── store.db
├── requirements.txt
└── .env.example
```

---

## 🚀 Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key_here
```

---

## 💬 Example Queries

```text
I want organic honey under $20
```

```text
Show me olive oil with rating above 4.5
```

```text
Find almonds below $15
```

Or upload a product image and let the AI find similar products automatically.

---

## 🌟 Highlights

✅ Multimodal AI (Text + Image)

✅ Vision-Powered Product Search

✅ LangChain Agent & Tool Calling

✅ Rating-Aware Recommendations

✅ Conversational Shopping Experience
