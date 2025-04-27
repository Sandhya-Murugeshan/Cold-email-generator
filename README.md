# 🛠️ Tech Stack
-> Python
-> Streamlit (Frontend)
-> ChromaDB (Vector database)
-> LangChain (WebBaseLoader)
-> OpenAI / Groq LLMs

# --Features--

-> AI-driven Cold Emails: Smart, context-aware cold email creation.
-> Vector Database (ChromaDB): Ultra-fast semantic search over portfolio data.
-> Streamlit UI: Rapid prototyping and beautiful frontend without heavy coding.
-> Web Scraping: Load and embed data from web pages with LangChain's WebBaseLoader.
-> Optimized Search: Locality Sensitive Hashing (LSH) for lightning-fast matching.



This project uses Generative AI and a Vector Database (ChromaDB) to automatically create smart, personalized cold emails. It loads portfolio data, converts it into embeddings, and performs fast semantic search using cosine similarity and locality sensitive hashing (LSH). It also supports scraping website text using WebBaseLoader and offers a quick user interface with Streamlit for easy testing. Fast, optimized, and ready for real-world use!

cold-email-generation-tool/
app/
 main.py            # Main app entry (could be Streamlit/CLI)
 
 chains.py          # Chain logic for generating emails
 
 portfolio.py       # Portfolio/project management
 
 utils.py           # Helper utilities
 
 resource/my_portfolio.csv # Example portfolio
 
notebooks/
chromadb.ipynb      # Vector DB experiments

email_generator.ipynb # Email generation experiments

groq.ipynb          # LLM/Groq model interaction

vectorstore/            # Stored vector database

requirements            # List of Python dependencies

.env                    # API keys and environment variables

# output
![Screenshot 2025-04-27 222151](https://github.com/user-attachments/assets/1ef88aac-b2c9-4bdc-94fb-d6cc8d433e65)


# 🚀 Run the Application

# backend
cd app
python main.py

# To launch the Streamlit UI (if integrated):

streamlit run app/main.py
