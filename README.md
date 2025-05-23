# mood-based-book-recommender

This project suggests books according to your current mood. It uses sentence embeddings to find books whose descriptions or the first sentences best match your emotion.

## How It Works

1. You enter your mood as a short sentence.
2. The system encodes book descriptions by a pre-trained SentenceTransformer model.
3. It compares your mood with each book description using cosine similarity.
4. It recommends the most relevant books to you.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- SentenceTransformers (`all-MiniLM-L6-v2`)

Don't skip to read my detailed writing on this project: https://medium.com/@busraracoban/what-should-i-read-when-i-feel-a-mood-based-book-recommender-built-with-python-and-ai-43fed1b4894f 

## Installation

```bash
pip install -r requirements.txt
