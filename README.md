# genai-solutions-course

Assignment 1: A Python notebook that loads a text file of 12 paragraphs, splits it into 500-character chunks with a 20% overlap, embeds the chunks with gemini-embedding-001, embeds the user's query with the same model, computes cosine similarity against every chunk, and prints the question with the top 3 chunks and their scores.

Assignment 2: A Python notebook that loads three text files from different fields, splits them with dynamic chunking at paragraph and sentence boundaries, embeds the chunks, and saves them in a FAISS vector database on disk with each chunk's text and file name. On later runs it loads the saved database and skips Phase 1, then embeds the user's query, searches with cosine similarity, and prints the top 3 chunks with their scores and file-name references.
