## Introduction
----------------------------
Build an information retrieval system (Q&amp;A bot) 
that can interface with your data (multiple pdf files) 
and accurately respond to queries related to the contents 
of these files. This Q&amp;A bot must be built using a 
generative AI service Hugging Face LLMs. Please note that the bot 
will only respond to queries which are within the scope 
of uploaded documents.

## Dependencies 
----------------------------
1. create .env file
   ```
   HUGGINGFACEHUB_APT_TOKEN= 
   ```
2. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   
   ```
## Usage
----------------------------
1. Run the `main.py` file using the Streamlit CLI. Execute the following command:
   ```
   streamlit run app.py --server.maxUploadSize=1028
   ```
2. Sample input PDFs are related to Harry Potter books
   ```
   HP books
   ```
