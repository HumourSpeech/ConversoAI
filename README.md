
# 📚 ConversoAI — AI-Powered Conversational PDF Assistant (https://huggingface.co/spaces/humourSpeech6076/ConversoAI)

ConversoAI is an intelligent RAG-based PDF assistant that allows users to **upload documents and interact with them like a chat**. Instead of scrolling through hundreds of pages, you can ask:

> *"Explain chapter 2"*,
> *"What are the key formulas?"*,
> *"Summarize the conclusions"*,
> *"What is the PDF talking about?"*

…and ConversoAI finds the answer instantly.

---

## 🚀 Why This Project?

As engineering students, we’ve all faced that all-too-familiar situation:

📄 A 200-page PDF  
⏳ One night before the exam  
😵 Endless scrolling to find *that one important concept*  

The real issue isn’t effort — it’s inefficiency.  
Key insights are buried in dense paragraphs. References lead to more references. Important definitions are scattered across pages. Under time pressure, extracting clarity becomes frustrating and overwhelming.

That frustration led to the creation of **ConversoAI**.

Instead of passively scrolling, what if you could **interact** with your study material?

Imagine uploading a document and simply asking:

- “Summarize this chapter.”
- “Explain this concept in simple terms.”
- “What are the key takeaways?”
- “How does this compare to another topic?”

**ConversoAI transforms static PDFs into interactive, context-aware conversations.**  
It allows you to extract exactly what you need — quickly, accurately, and intelligently.

Because studying shouldn’t be about scrolling harder.  
It should be about understanding smarter.


## 🧠 Features

* 📁 **Upload Multiple PDFs**
* 🤖 **Conversational Retrieval-Augmented Generation (RAG)**
* 🧵 **Persistent Session-based chat history**
* ⚡ **Powered by Groq LLM + HuggingFace embeddings**
* 🔍 **Semantic Search over long documents**
* 🖥️ **Modern Gradio Interface**
* 🧠 **Understands context, reformulates questions, and retrieves relevant answers**

---

## 🛠️ Tech Stack

| Technology                     | Purpose                              |
| ------------------------------ | ------------------------------------ |
| **Python**                     | Core language                        |
| **Gradio**                     | Frontend UI                          |
| **LangChain**                  | RAG pipeline + chat memory           |
| **ChromaDB**                   | Vector storage                       |
| **HuggingFace Embeddings**     | Text embeddings (`all-MiniLM-L6-v2`) |
| **Groq API (Gemma / Mixtral)** | LLM response generation              |
| **PyPDFLoader**                | Document parsing                     |

---

## ⚙️ Installation

Clone the repo:

```bash
git clone https://github.com/HumourSpeech/ConversoAI.git
cd ConversoAI
```

Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Create a `.env` file:

```
HUGGING_FACE_API_KEY=your_hf_api_key
GROQ_API_KEY=your_groq_api_key
```

---

## ▶️ Run the App

```bash
gradio app.py
```

Then open:

👉 `http://127.0.0.1:7860/` in your browser.

---

## 🧪 How to Use

1. Enter your **Groq API key(optional)**
2. Upload one or more **PDFs**
3. Click **Build Knowledge Base**
4. Start chatting — ask questions like:

```
What is the conclusion?
Explain page 23.
Give me a summary of chapter 5.
```

---

## Future Enhancements

* Voice-based querying
* Mobile UI
* Support more file formats (DOCX, PPT, Research papers)
* Personalized study summaries + flashcards

---

## Contribution

Pull requests are welcome!
If you'd like to propose major changes, please open an issue first.

---

## Credits

Built with love, curiosity, and desperation one night before exams 😄

---

### If ConversoAI helped you study better — don’t forget to star the repo!

---



