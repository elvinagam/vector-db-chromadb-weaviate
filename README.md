# vector-db-chromadb-weaviate
Experiments on vector databases with LLMs


![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)

## Description

This project explores the fascinating intersection of Vector Databases, Weaviate, and Language Models (LLMs). It aims to leverage the power of vector databases and Weaviate, an open-source knowledge graph, to enhance the capabilities of Language Models.

The project focuses on developing novel techniques and tools to enable efficient storage, retrieval, and querying of large-scale vectorized data in Weaviate. By integrating Weaviate with LLMs, we can leverage contextual information and semantic understanding for various applications such as natural language processing, information retrieval, recommendation systems, and more.

Key Features and Objectives:

Efficient vector storage and indexing in Weaviate
Seamless integration of Weaviate with popular Language Models
Advanced querying capabilities for vector-based search
Supporting use cases in natural language processing, information retrieval, and recommendation systems
Comprehensive documentation and examples for easy adoption

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

To install and set up the project locally, follow these steps in the colab file
Needed packages:

Tiktoken - for Byte Pair Encoding used in OpenAI and HF models
huggingface-hub - fetching pretrained models
chromadb - vector DB
sentence_transformers - by default, Chroma uses Sentence Transformers to create embeddings. Sentence Transformers is a library for creating sentence and document embeddings that can be used for a wide variety of tasks. It is based on the Transformers library from Hugging Face. This embedding function runs locally on your machine, and may require you download the model files (this will happen automatically).
langchain - LLM chaining
openai - for fetching AI API



## Usage

use it for walkthrough and understadning of why we need vector databases
## Contributing


We welcome contributions from the community! If you'd like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Please see the \`LICENSE\` file for more details.

## Contact

Provide contact information for users to reach out to you if they have any questions or concerns. This can include your email address, social media profiles, or links to relevant communication channels.

For any inquiries, please feel free to reach out to me at [email@example.com](mailto:elvinagammed@gmail.com).

---
Feel free to include any additional sections or information that is relevant to your project. Make sure the README file is well-organized, easy to read, and visually appealing.
`;

console.log(readmeContent);

