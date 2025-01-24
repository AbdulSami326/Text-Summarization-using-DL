 Text Summarizer using BART 

This project demonstrates a Text Summarizer built using the BART (Bidirectional and AutoRegressive Transformers)** model from Hugging Face's Transformers library. The application uses Gradio to provide an interactive web interface for generating concise and meaningful summaries of long texts.

---

Features

- Model: `facebook/bart-large-cnn` for abstractive text summarization.
- Interactive Interface: Built with Gradio for easy usability.
- Customizable Inputs: Users can enter up to 1024 characters of text to generate summaries.
- Dynamic Summaries: The summarizer generates output with configurable length and beam search for better results.

---

Installation

To set up the project locally, follow these steps:

Prerequisites
- Python 3.7 or later
- Install the required Python libraries: 

bash
pip install transformers gradio torch
