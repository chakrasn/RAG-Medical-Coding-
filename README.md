# RAG-Medical-Coding-
A RAG based approach to code clinical discharge summaries to ICD-9 diagnosis and procedure codes
In the healthcare insurance industry, physicians must be reimbursed precisely for the services they provide to insured patients. In this context, one of the biggest challenges is medical coding, which is the process of translating a physician and patient interaction into a standard set of diagnosis codes (ICD10 – International Classification of Diseases) and procedure codes (CPT – Current Procedural Terminology). This scenario is suitable for automation using AI (Artificial Intelligence) to assist coding specialists in generating medical codes. 

 


Clinical notes and transcriptions often contain complex medical terms, which may not have been taught by a novice Large Language Model (LLM). LLM models are adept at generating text based on patterns learned during training but fall short when faced with queries requiring specific and up-to-date information in clinical notes and changing ICD, CPT codes. Retrieval Augment Generation (RAG) models begin by retrieving a set of documents relevant to the given query or context and integrating the retrieved data to craft contextually rich response. This approach allows for improved precision and relevant responses to clinical notes query, particularly when the clinical note query requires an updated ICD/CPT code and specialized clinical information. 
