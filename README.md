# 🍽️ RAG-Gen-AI-Restaurant-Chatbot

An AI-powered restaurant assistant built using Retrieval-Augmented Generation (RAG), vector search, and Large Language Models to provide intelligent food recommendations and natural conversational interaction.

The system combines restaurant menu data, semantic retrieval, and LLM-based reasoning to help users discover dishes, explore cuisines, compare food items, and interact with restaurant information through natural language queries.

---

# 🚀 Features

- 🔍 AI-powered semantic food search
- 💬 Conversational restaurant assistant
- 📄 Retrieval-Augmented Generation (RAG) pipeline
- 🧠 Context-aware query understanding
- 🍕 Personalized food and cuisine recommendations
- 📚 Vector similarity search using Pinecone
- 🗂️ Structured restaurant and menu knowledge base
- ⚡ Fast and scalable retrieval workflow
- 🌐 Interactive frontend interface

---

# 🧠 Problem Statement

Traditional food ordering platforms rely heavily on keyword-based search and static filtering systems, which often fail to understand natural language queries such as:

- “Suggest spicy vegetarian dishes under ₹300”
- “Recommend high-protein meals for dinner”
- “What are the best Italian dishes available?”

This project addresses the limitation by integrating LLM-based conversational intelligence with semantic retrieval to provide more accurate and context-aware food recommendations.

---

# 🏗️ System Architecture

The project follows a Retrieval-Augmented Generation (RAG) workflow:

1. Restaurant and menu data are collected and structured.
2. Menu information is converted into embeddings.
3. Embeddings are stored inside Pinecone vector database.
4. User queries are converted into vector representations.
5. Similar menu items are retrieved using semantic similarity search.
6. Retrieved context is passed to the LLM.
7. The LLM generates context-aware responses and recommendations.

---

# ⚙️ Tech Stack

## Programming Language
- Python

## AI/ML Technologies
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Embeddings
- NLP Pipelines

## Libraries & Frameworks
- LangChain
- Pinecone
- Google Gemini API
- Sentence Transformers
- Streamlit
- Pandas
- NumPy

## Database & Storage
- Pinecone Vector Database
- JSON-based Knowledge Base

---

# 📂 Project Structure

```bash
Restaurant-Gen-AI-Chatbot/
│
├── data/                     # Restaurant and menu datasets
├── embeddings/               # Embedding generation pipeline
├── prompts/                  # Prompt templates
├── scraper/                  # Data collection and scraping scripts
├── vector_store/             # Pinecone integration
├── app.py                    # Main application
├── requirements.txt          # Python dependencies
├── README.md
└── utils/                    # Helper utilities
```

---

# 🔄 Workflow Pipeline

## 1. Data Collection
Restaurant and menu information are collected and transformed into structured JSON format.

## 2. Data Preprocessing
Menu descriptions, cuisine types, and food metadata are cleaned and formatted.

## 3. Embedding Generation
Text embeddings are generated for semantic similarity search.

## 4. Vector Storage
Embeddings are stored in Pinecone for efficient retrieval.

## 5. Query Understanding
User queries are converted into embeddings and matched against the vector database.

## 6. Context Retrieval
Relevant restaurant and menu information is retrieved.

## 7. Response Generation
The LLM generates contextual and conversational responses based on retrieved information.

---

# 📊 Key Functionalities

## 🍔 Intelligent Food Recommendation
Provides personalized food suggestions based on:
- Cuisine preferences
- Dietary requirements
- Budget constraints
- Meal type
- Taste preferences

## 🔍 Semantic Menu Search
Understands intent-based natural language queries instead of relying only on keyword matching.

## 💬 Conversational AI Experience
Supports interactive and context-aware conversations for restaurant discovery.

## 📚 RAG-based Information Retrieval
Improves response quality by grounding LLM outputs using retrieved restaurant data.

---

# 🛠️ Installation & Setup

## 1. Clone Repository

```bash
git clone https://github.com/himanshukumar8/RAG-Gen-AI-Restaurant-Chatbot.git
cd RAG-Gen-AI-Restaurant-Chatbot
```

## 2. Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Windows
```bash
venv\Scripts\activate
```

#### Linux/Mac
```bash
source venv/bin/activate
```

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 4. Configure Environment Variables

Create a `.env` file:

```env
PINECONE_API_KEY=your_api_key
GEMINI_API_KEY=your_api_key
```

## 5. Run Application

```bash
streamlit run app.py
```

---

# 📈 Challenges Addressed

- Handling irrelevant retrieval results
- Improving semantic similarity search quality
- Reducing hallucinated responses
- Structuring restaurant data efficiently
- Managing context-aware conversations
- Optimizing retrieval latency

---

# 🔍 Future Improvements

- Multi-language support
- Voice-based food assistant
- Personalized recommendation engine
- Real-time restaurant availability
- Hybrid search (keyword + semantic search)
- User preference memory
- Feedback-based recommendation optimization

---

# 📌 Learning Outcomes

This project helped strengthen understanding of:

- Retrieval-Augmented Generation (RAG)
- Vector databases and embeddings
- Semantic search systems
- Prompt engineering
- LLM integration workflows
- NLP-based conversational systems
- End-to-end AI application development

---

# 📄 License

This project is intended for educational and learning purposes.

---

# 👨‍💻 Author

Himanshu Kumar

- GitHub: https://github.com/himanshukumar8
- LinkedIn: https://www.linkedin.com/in/himanshuhhk/