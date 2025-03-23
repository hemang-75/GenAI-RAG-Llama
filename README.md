# GenAI-RAG-Llama
Document QnA using Llama3

This project leverages Llama 3.2 model and Streamlit to create a 100% locally running Document Question Answering app that can perform QnA against the documents uploaded by the user

## Installation and setup

**Setup Ollama**:
   ```bash
   # setup ollama on linux 
   curl -fsSL https://ollama.com/install.sh | sh
   # pull Llama3.2 model
   ollama run llama3.2
   ```

**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install -r requirements.txt
   ```

**Launch the Streamlit App**:
    After doing all the setup and installations, run the following command in your terminal
    ```bash
    streamlit run rag_ollama.py
    ```
This is how it will look :

![image 1](images/img_1.png)
![image 2](images/img_2.png)
![image 3](images/img_3.png)

