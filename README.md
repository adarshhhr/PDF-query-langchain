# PDF Query Tool

The PDF Query Tool is a Python project that allows you to query the text content of PDF files using natural language questions. It makes use of several libraries and tools to perform this task efficiently.

## Files in this Repository

### File1: "example.pdf"

This is the PDF file that we want to query. It serves as an example document for the PDF Query Tool. Replace this with your pdf

### File2: `requirements.txt`

The `requirements.txt` file contains the list of Python packages required to run this project. You can install these dependencies using the following command:

###File3: 'PdfQuery.ipynb'

The PdfQuery.ipynb notebook is the heart of this project. It contains Python code that demonstrates how to use the PDF Query Tool. Here are the main steps performed in this notebook:

Install the project dependencies listed in requirements.txt.
Extract text content from the PDF file 'example.pdf'.
Split the extracted text into manageable chunks.
Generate text embeddings using OpenAI's language model.
Build a vector store using FAISS for efficient text searching.
Use a pre-trained question-answering model to answer questions based on the PDF content.

###Usage

To use the PDF Query Tool, follow these steps:

Install the required dependencies by running pip install -r requirements.txt.

Open the PdfQuery.ipynb notebook in a Jupyter environment or your preferred Python IDE.

Execute the code cells in the notebook to perform PDF text querying based on natural language questions.
To run this notebook, make sure to install the required dependencies and set your OpenAI API key as specified in the code.

###Contributors
[Adarsh]

###Acknowledgments
OpenAI for their language model and tools used in this project.
Feel free to explore and adapt this project to suit your needs. If you have any questions or suggestions, please don't hesitate to contact the project contributors.


