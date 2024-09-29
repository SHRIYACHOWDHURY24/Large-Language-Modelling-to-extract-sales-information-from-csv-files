# Large-Language-Modelling-to-extract-sales-information-from-csv-files
 The project involves developing a language model (LLM) for extracting sales information from CSV files using advanced machine learning and natural language processing techniques. The model leverages several Python libraries and algorithms to process and analyze data efficiently

# Software and Python Libraries Used:
Python, Langchain, OpenAI, Chromadb, Tiktoken
# Mechanisms and Algorithms: 
1.Document Loading: CSVLoader from Langchain is used to load data from CSV files

2. Index Creation: VectorstoreIndexCreator from Langchain creates an index of the loaded documents to facilitate fast retrieval
   
3. Question-Answering Chain: RetrievalQA chain from Langchain, combined with OpenAI’s language model, processes queries and retrieves relevant information
   
4. Vector Store: A mechanism to efficiently store and retrieve document vectors for quick data access.

