# **Streamlit Data Assistant with Chatbot**

## **Overview**
A **Streamlit-powered web application** that allows users to upload datasets (CSV, Excel), manipulate data types, and interact with a **Language Model (LLM)** to analyze and query data in a conversational format. The application enables data transformations such as changing data types, renaming columns, and running queries using the chatbot powered by **LangChain**.

---

## **Features**
- **Upload Dataset**: Allows users to upload CSV or Excel files.
- **Change Data Types**: Change column data types (int, float, string, datetime).
- **Rename Columns**: Rename columns in the dataset.
- **Chatbot Interaction**: Chat with a Language Model to query the dataset and analyze data.
- **Persist Data**: All user interactions are stored and persisted across sessions using **Streamlit’s session state**.
- **handle duplicated values**
- **handle missing values**

---

## **Technologies Used**
- **Streamlit**: For creating the interactive web interface.
- **Pandas**: For data manipulation and handling.
- **LangChain**: To integrate and interact with Language Models.
- **Ollama**: For integrating with a local LLM(llama3.2:1b) for querying data.
- **Python**: Core programming language for backend functionality.

---

## Acknowledgments
We would like to thank the following:
- **Streamlit** for providing the app framework.
- **LangChain** for enabling the use of language models.
- **Ollama** For the pre-trained language model that powers the chatbot.
---


## Steps to Run the App
1. Clone the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the app with `streamlit run quality.py`.
---

### **Clone the repository:**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
## **Install dependencies:**
pip install -r requirements.txt


> ⚠️ **Warning:** Make sure to follow the installation instructions carefully to avoid errors and install locall model (llama3.2:1b).







