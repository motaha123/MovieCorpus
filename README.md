This project analyzes the **CMU Movie Summary Corpus** using **NLTK** for Natural Language Processing tasks.  
It covers:
- Tokenization and unique token counts
- Lexical diversity measurement
- Verb lemmatization
- Word frequency stats
- Part-of-speech tagging
- Average sentence length
- Simple spelling corrector using Jaccard and Edit Distance

---

## ✅ How to Use

1. Make sure you have **Python** and **NLTK** installed.

   ```bash
   pip install nltk
Download required NLTK resources:

python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
nltk.download('words')
Put your plots.txt file inside the assets/ folder.

Run the Python script:

bash
Copy
Edit
python your_script_name.py
📌 Notes
All data is used under a Creative Commons license.

For the spelling recommender, the built-in NLTK word corpus is used.

This project was built as part of an NLP learning assignment.

