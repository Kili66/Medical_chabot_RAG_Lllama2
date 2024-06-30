# End-TO-End Medical_chabot using Lllama2 with RAG

## Steps to run the project

* Create a new environment
```bash
conda create -n metachatbot python==3.8 -y
```
* Activate the environment
```bash
conda activate metachatbot
```
* Install all dependencies

```bash
pip install -r requirements.txt
```

#### Use Pinecone API
####  Embedding model from Hugging Face: all-MiniLM-L6-v2 Usage (Sentence-Transformers)
* This is a sentence-transformers model: It maps sentences & paragraphs to a 384 dimensional dense vector space and can be used for tasks like clustering or semantic search.
* Create Pincone ENV 

