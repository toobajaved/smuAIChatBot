# SMU FAQ Chatbot

This project is an AI-powered chatbot designed to assist students by answering frequently asked questions (FAQs) related to Saint Mary's University (SMU). Leveraging the `sentence-transformers/all-MiniLM-L6-v2` model and FAISS for efficient similarity search, the chatbot provides accurate and relevant responses based on a curated dataset.

## Project Contents

This repository contains the following files:

- `README.md` – Provides an overview of the project and usage instructions.
- `chatbot.ipynb` – The main notebook that trains and runs the SMU FAQ Chatbot.
- `LICENSE` – This project is licensed under the MIT License.

## Check Out the Dataset

The dataset used to train the chatbot has been meticulously curated by me and is available on Hugging Face:

[SMU_FAQDataset on Hugging Face](https://huggingface.co/datasets/tootooba/SMU_FAQDataset)

## What Does This Chatbot Do?

The SMU FAQ Chatbot is designed to answer student inquiries by leveraging a dataset of frequently asked questions and their corresponding answers. For instance, you can ask questions like "What is the academic calendar?" or "How do I apply for a co-op position?" and receive accurate and contextually relevant answers.

## How to Use the Chatbot

### Running the Chatbot Locally with Python

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/tootooba/smuAIChatBot.git
   cd smuAIChatBot

2. **Install Required Libraries:**

  Ensure you have Python installed (preferably Python 3.8 or higher). Install the necessary packages  using pip:
  
   ```bash
  pip install -r datasets torch transformers faiss-cpu

```
3. **Run the Chatbot:**

Open the SMU_FAQ_Chatbot.ipynb notebook in Jupyter Notebook or JupyterLab and execute the cells to start the chatbot.

## Author

This project was developed by **Tooba Javed**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Hugging Face** for providing robust tools and models for natural language processing.
- **FAISS** for enabling efficient similarity search and clustering of dense vectors.



