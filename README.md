# GenAI
RAG based Q&A for Manufacturing Products

Background:
Our client (Manufacturer A) is a leading home appliance, power tools, hardware manufacturer. Client wants to answer the customer queries related to the products using the product manuals

Client will provide the following data for the project:
Product Manuals – PDF documents of the product manuals
User Queries – List of expected user queries per product
Ground Truth – Expected retrieved context and answers for every query

Deliverables:
Data Preparation & Exploration
Demonstrates:
Provide a report on parsers tried with advantages and disadvantages based on data, language
Provide a report on metadata to be used for document chunks
Provide a report on type of chunking methods and splitters available with details of splitting technique, chunk size measurement criteria and other obeservations
Provide a report on experiments of #chunks created, chunk size, chunk overlap, tokens per chunk for the llm used
Provide a report on parsing time, final chunk size, chunk overlap, chunk processing and top k selected for the analysis

Retriever
Demonstrates:
Provide a report on retriever embeddings and database used with potential advantages & disadvantages
Implement an approach to de-duplicate the data for retriever
Provide a report on chunking time, embedding time and indexing time for the final chunks. Include any other data processing latencies

RAG based QnA

Demonstrates:
Identify the LLM to be used for answering questions
Create a retrieval and QnA pipeline to answer the user query
Provide a report on database loading time, query embedding time, retrieval time, summarization time, model load time, model GPU/CPU usage. Include any other processing latencies across queries
Provide a report on tokens consumed, prompts and chain types used across queries
Provide a final report on the best chunk parameters, retriever parameters, prompt parameters and LLM model parameters 
Provide a report with metrics used to justify the final parameters selections
Retrieval level metrics
Final answer level metrics

Business Outcomes 
Tool to answer any user query and the most relevant documents with page number
Summary of key metrics mentioned in the excel
Github link for the final codes
Excel / MLFlow with the key metrics, answers and top k documents for every query (Note - make sure to add chunk params, LLM model, embeddings and vector database used)

