# Frameworks-Of-Gen-AI
This repository contains easy implementation of all the frameworks of GenAI_2024

# Llama Index

Llama Index is a powerful tool for handling and retrieving information. Here are some of its key features and benefits:

## Key Features and Benefits

- **Versatile:** Llama Index can connect to various data sources, making it a versatile tool for handling different types of data.
- **User-friendly:** Llama Index has a simple and intuitive interface that makes it easy to use, even for those who are not tech-savvy.
- **Scalable:** Llama Index can handle large datasets, making it a great tool for businesses and organizations with large amounts of data.
- **Fast:** Llama Index uses advanced algorithms to quickly and efficiently retrieve relevant information, saving users time and effort.

## Installation and Environment Setup

To get started with Llama Index, you will need to import the necessary libraries and set up your environment for code execution. Here are the steps to follow:

1. **Install the Llama Index library:** You can install the Llama Index library using pip, the Python package installer. Just run the following command in your terminal or command prompt:

    ```
    pip install lama-index
    ```

2. **Import the Llama Index library:** Once you have installed the Llama Index library, you can import it into your code by adding the following line at the top of your script:

    ```python
    import lama_index as li
    ```

3. **Set up your environment:** Before you can start using Llama Index, you will need to set up your environment for code execution. This includes installing any necessary dependencies and configuring your environment variables.

## Connecting Custom Data Sources

Llama Index has various data connectors that allow you to connect custom data sources. Here are some of the data connectors available in Llama Index:

- **CSV Connector:** This connector allows you to connect CSV files to Llama Index.
- **JSON Connector:** This connector allows you to connect JSON files to Llama Index.
- **SQL Connector:** This connector allows you to connect databases to Llama Index.
- **Web Crawler Connector:** This connector allows you to crawl and index data from websites.

## The Query Engine

The query engine is a concept in Llama Index that allows you to retrieve relevant information. The query engine works by using advanced algorithms to search the index and retrieve the most relevant results.

## Storing and Accessing Data

Llama Index supports various data storage formats, including CSV, JSON, and SQL. Once you have connected a data source and indexed the data, you can retrieve the information using the query engine.

## Introduction to Pine Cone and Llama Index Integration

Llama Index can be integrated with Pine Cone, a vector database that allows you to perform advanced vector searches. By integrating Llama Index with Pine Cone, you can enhance the capabilities of Llama Index and perform complex vector searches.

## Working with PDF Documents

Llama Index supports indexing and searching PDF documents. Here are the steps to follow to index a PDF document in Llama Index:

1. **Install the PyMuPDF library:** You can install the PyMuPDF library using pip, the Python package installer. Just run the following command in your terminal or command prompt:

    ```
    pip install PyMuPDF
    ```

2. **Import the PyMuPDF library:** Once you have installed the PyMuPDF library, you can import it into your code by adding the following line at the top of your script:

    ```python
    import fitz
    ```

3. **Load the PDF document:** You can load the PDF document using the `fitz.open()` function.

4. **Extract the text:** You can extract the text from the PDF document using the `get_text()` function.

5. **Create a text node:** You can create a text node from the PDF text using the `TextNode` class in Llama Index.

6. **Add the text node to the index:** You can add the text node to the index using the `add_document()` method.

## Llama Index vs Others

Llama Index is an alternative to other data handling tools like Lang chain and Pine Cone. Here is how Llama Index compares to these tools:

- **Lang chain:** Lang chain is a language model that can be used for various NLP tasks. Llama Index, on the other hand, is a tool for handling and retrieving information and can be used in conjunction with a language model like Lang chain.
- **Pine Cone:** Pine Cone is a vector database that allows you to perform advanced vector searches. Llama Index can be integrated with Pine Cone to enhance its capabilities and perform complex vector searches.

In conclusion, Llama Index is a powerful tool for handling and retrieving information, with various data connectors, a user-friendly interface, and advanced query capabilities. Whether you are a student, researcher, or business owner, Llama Index can help you manage and make sense of your data.
