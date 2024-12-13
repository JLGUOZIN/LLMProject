# **LLMProject: OpenAI and Llama Integration for Intelligent Chatbots**

Welcome to **LLMProject**, a cutting-edge solution for building intelligent and context-aware chatbots! This project integrates the latest **OpenAI GPT models** and **Llama libraries**, combining state-of-the-art natural language processing with robust tool-handling capabilities to deliver an interactive, extensible chatbot.

---

## **What Does This Project Do?**
LLMProject focuses on creating a seamless and interactive chatbot experience by:
1. **Providing accurate and context-aware responses** for customer inquiries, specifically designed for an **Ecommerce Website** (e.g., Sift & Pick).
2. Integrating **function calling capabilities** to fetch real-time data (e.g., product prices) using tools powered by the **OpenAI GPT-4** model.
3. Supporting **data crawling and extraction** via the **Llama library**, allowing automated content retrieval from websites like "About Us" pages.

---

## **Key Features**
### **1. OpenAI GPT Integration**
- Uses the latest **GPT-4** and **GPT-4o-mini** models.
- Implements advanced **tool-handling** to dynamically call external APIs for additional information, such as retrieving product prices.

### **2. Llama Library for Crawling**
- Incorporates **Llama's API** for efficient crawling and structured data extraction.
- Enables automated parsing of web pages (e.g., extracting company information) and feeding it into the chatbot for enhanced responses.

### **3. Interactive Chat Interface**
- Leverages **Gradio** for an intuitive web-based chat interface.
- Supports seamless interaction between user queries and tool-driven backend processes.

### **4. Extensible Design**
- Modular architecture to easily add new tools or functionality.
- Customizable prompts and behavior for domain-specific applications (e.g., Ecommerce).

---

## **Installation**

### **Prerequisites**
Ensure you have the following installed:
- Python 3.8 or later
- OpenAI Python SDK (latest version)
- Llama API library
- Gradio library

### **Setup Instructions**
1. Clone this repository:
   ```bash
   git clone https://github.com/JLGUOZIN/LLMProject.git
   cd LLMProject
