# Codebase-rag

The code base used in this project is https://github.com/CoderAgent/SecureAgent

Below is a professional and visually appealing README.md template with sections and styles tailored for your project:

---

# **Codebase Conversational Assistant**

*Interact with your codebase using natural language queries powered by RAG and LLMs.*

---

## **Table of Contents**
1. [About the Project](#about-the-project)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Getting Started](#getting-started)
5. [Usage](#usage)
6. [Skills Gained](#skills-gained)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

---

## **About the Project**
The **Codebase Conversational Assistant** is an intelligent chatbot that enables users to interact with their codebase via natural language queries. By leveraging Retrieval-Augmented Generation (RAG) and Large Language Models (LLMs), the system fetches relevant code snippets, provides insightful answers, and streamlines the process of understanding complex codebases.

### **Objective**:
To simplify codebase exploration by offering an AI-powered assistant capable of answering contextually rich questions about any given GitHub repository.

---

## **Features**
- Fetches and processes files from a specified GitHub repository.
- Generates and stores embeddings in Pinecone for efficient retrieval.
- Performs vector similarity search to identify relevant code snippets.
- Integrates with OpenAI's LLMs to answer user queries in natural language.
- Provides an interactive and user-friendly chatbot interface using Streamlit.

---

## **Technologies Used**
- **Python**: Core programming language.
- **Streamlit**: For building the web-based chatbot interface.
- **Pinecone**: Vector database for efficient code retrieval.
- **OpenAI**: GPT-based models for generating responses.
- **SentenceTransformer**: For generating semantic embeddings.
- **GitHub API**: To fetch code repositories programmatically.

---

## **Getting Started**
Follow the steps below to set up and run the project locally.

### **Prerequisites**
- Python 3.8 or higher
- Git
- A valid OpenAI API key
- A valid Pinecone API key

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/vidhi-01/Codebase-rag
   cd codebase-rag
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file and add your keys:
   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   PINECONE_API_KEY=your_pinecone_api_key
   PINECONE_ENV=your_pinecone_environment
   ```

---

## **Usage**
1. Start the Streamlit application:
   ```bash
   streamlit run app.py
   ```
2. Open the app in your browser using the URL provided by Streamlit.
3. Enter your queries in the chatbot interface to interact with your codebase.

---

## **Skills Gained**
- **Natural Language Processing (NLP)**: Using sentence embeddings and vector similarity search.
- **Machine Learning Engineering**: Integrating RAG and LLMs.
- **Full-stack Development**: Combining Python, APIs, and web frameworks.
- **Cloud Integration**: Configuring Pinecone for high-dimensional vector storage.

---

## **Contributing**
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## **Contact**
**Your Name**  
Email: [vpatel40@stevens.com](mailto:vpatel40@stevens.com)  
