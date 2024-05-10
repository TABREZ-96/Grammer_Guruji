# Grammar Guruji

Grammar Guruji is an interactive web application powered by Streamlit, designed to correct grammatical errors in text using state-of-the-art NLP models. It leverages the Hugging Face Transformers library and Optimum Intel OpenVINO integration for efficient model inference.

![WhatsApp Image 2024-05-06 at 20 15 32_2be87033](https://github.com/TABREZ-96/Grammer_Guruji/assets/114156392/b0fe0f8e-93eb-4791-b691-d40541b82a0d)


## Features

- **Sentence Splitting**: Breaks down text into individual sentences for better context understanding.
- **Grammar Checking**: Utilizes a robust model to identify grammatical errors.
- **Grammar Correction**: Offers suggestions to improve the text's grammar.
- **Streamlit Interface**: Provides an easy-to-use web interface for real-time grammar correction.

## Models

The application uses two primary models:

1. **Grammar Checker**: `textattack/roberta-base-CoLA` - A model trained on the Corpus of Linguistic Acceptability (CoLA) for grammatical error detection.
2. **Grammar Corrector**: `pszemraj/flan-t5-large-grammar-synthesis` - A model that generates grammatically correct sentences.

Both models are optimized with Intel OpenVINO for faster inference on CPU.

## Installation

To set up Grammar Guruji, follow these steps:

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/grammar-guruji.git](https://github.com/TABREZ-96/Grammer_Guruji/)
   ```

2. Install the required packages:

## Usage

To start the application, run:
```streamlit run main2.py```


Navigate to `http://localhost:8501` in your web browser to access the Grammar Guruji interface.

## Acknowledgments

- Hugging Face for the Transformers library.
- Intel for the Optimum library and OpenVINO toolkit.
- The developers and researchers behind the CoLA dataset and T5 models.

---

For more information on the models and their usage, please refer to the official documentation of Transformers and Optimum.

