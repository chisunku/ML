# Objective 
This project focused on integrating Weaviate, a vector database, with a local Large Language Model (LLM), specifically targeting enhanced NLP tasks around the works and historical context of William Blake. It aimed to leverage the synergies between database-driven context retrieval and the generative capabilities of LLMs for nuanced natural language processing. 

## Methodology 
- Setup and Dependencies: Initiation involved installing necessary packages and importing dependencies, including HuggingFace's sentence transformer for embedding and the 'zephyr-7b-alpha-sharded' model for the LLM. 
- Weaviate Configuration: The embedding model 'sentence-transformers/all-mpnet-base-v2' was specified for Weaviate, with model arguments set for CUDA optimization, ensuring efficient processing. Data Ingestion into Weaviate: Over 30 poems by William Blake and multiple articles detailing significant historical events during his lifetime were ingested into Weaviate's vector database for semantic searches and contextual retrievals. Local LLM Setup: The LLM was loaded with 4-bit quantization to balance performance and resource usage. A custom tokenizer was initialized to align with the specific model requirements, including the setting of special tokens. Conversation Chain
- Implementation: Two approaches were employed for generating responses:
- Direct LLM Prompting: The model was queried directly with prompts related to Blake's life and works.
- RAG Augmentation: The Retrieval-Augmented Generation approach combined direct LLM responses with contextually relevant information pulled from Weaviate's database. 

## Experiments and Results 
Direct LLM Responses: These responses, while informative, generally lacked depth in historical details and specific connections to Blake’s work. RAG-Enhanced Responses: This approach yielded more detailed and contextually rich responses, integrating specific historical events and their implications on Blake's poetry. 

## Comparison and Evaluation: 
- Without RAG: The responses were broader, touching upon general themes in Blake's poetry but missing specific historical context.
- With RAG: Demonstrated a remarkable improvement in specificity and relevance, showcasing the efficiency of integrating vector database retrieval with LLMs. 

Example 
Query: "How is William Blake's 'Songs of Innocence and of Experience' related to 'The Slave Trade'?" 
- Without RAG: Response generalized Blake's themes in poetry, veering away from the specific query.
- With RAG: Response specifically linked "The Little Black Boy" from Blake's collection to the anti-slavery campaign, highlighting Blake's stance against slavery and racism. 

## Key Findings 
Enhanced Contextual Understanding: RAG's integration with Weaviate significantly improved the LLM's ability to provide context-specific information, especially concerning historical events and literary analysis. 
Accuracy and Relevance: RAG-augmented responses were more aligned with the query’s intent, offering a nuanced understanding not achievable by the LLM alone. 
Efficiency in Information Retrieval: The combination of Weaviate's vector database and the LLM facilitated efficient information retrieval, showcasing the potential for complex query handling in literary and historical research. 

## Conclusion 
The fusion of Weaviate's vector database capabilities with a locally hosted LLM creates a powerful tool for advanced NLP tasks. This hybrid system excels in providing detailed, contextually relevant responses, especially in fields requiring deep understanding, such 
as literature and history. The project underscores the potential of this integrated approach in enhancing the quality of responses for complex queries, offering a promising direction for future research and applications in AI-driven historical and literary analysis. The success in addressing queries related to William Blake demonstrates the model’s applicability in educational and research settings, where accuracy and depth of context are paramount. 
