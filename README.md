# Text Summarization 

This project presents a text summarization system capable of generating concise and coherent summaries from long text documents. Using Natural Language Processing (NLP) techniques, the system supports extractive, abstractive, and hybrid summarization modes.


# Features

-  Input long text or upload .txt files  
-  Extractive Summarization (selects key sentences)  
-  Abstractive Summarization (generates new sentences)  
-  Hybrid Summarization (combines both methods)  
-  Adjustable summary length  
-  Interactive Streamlit web interface
-
-  # Tools and Libraries

- *Python 3*
- *Streamlit* – Web UI
- *NLTK* – Tokenization & preprocessing
- *HuggingFace Transformers* – Abstractive summarization
- *Scikit-learn / NumPy* – Utility support



# How to Run

1. *Clone the repository*

   git clone https://github.com/Shibin08/Text-Summarization.git
   cd Text-Summarization/TEXT_SUMMARIZATION_PROJECT

2. *Create a virtual environment*

   python -m venv venv
   source venv/bin/activate    # On Windows: venv\Scripts\activate

3. *Install dependencies*

   pip install -r text_summarization/requirements.txt

4. *Download NLTK data*

   python text_summarization/fix_nltk.py

5. *Launch the app*

   streamlit run text_summarization/app.py

6. *Access the app*
   Open your browser and go to: http://localhost:8501




# Team Members — Group No. 32

Santwana Behera(Team Leader)

Shibin Malakot

Mohammad Rakshanda

Majji Vivek
