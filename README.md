# Movie Name Recommendation RAG

Project that preprocesses movie data and implements a Retrieval-Augmented Generation (RAG) movie-name recommendation pipeline using:
- Chroma (vector DB)
- sentence-transformers for embeddings
- optional OpenCV preprocessing and other utilities
- Scraper for movie data

Quick start
1. Create virtual env:
   python3 -m venv .venv
   source .venv/bin/activate

2. Install dependencies:
   pip install -r requirements.txt

3. Run preprocessing / notebook:
   jupyter lab  # or open preprocessing/movie.ipynb in VS Code

4. Create Chroma DB and run vectorization script (example):
   python preprocessing/chroma_example.py
