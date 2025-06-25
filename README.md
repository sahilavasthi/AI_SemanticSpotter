# Project Name
AI_SemanticSpotter


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- **Project Background**:
We will be building a Semantic Spotter AI project related to the uber 10-K financial and insurance industry forms. An AI-powered project to extract information from these documents can revolutionize how policies are analyzed and understood. Using natural language processing (NLP) / LlamaIndex framework , this system can efficiently scan, interpret, and extract key details such as coverage limits, exclusions, claim procedures, and premium details from the policy documents
- **Project Goal**:
Solving the above two requirements well in the project would ensure that the accuracy of the overall model is good and therefore further improvisations and customizations make sense
- **Problem Statement**:
Provided with Uber's 2021 financial statement Form 10-K & HDFC Bank Life Insurance policy statements. Our goal here is to build a RAG application on the annual financial statement pdf and life insurance policy documents
- **Tools used**:
**LlamaIndex** has been used due to its powerful query engine, fast data processing using data loaders and directory readers as well as easier and faster implementation using fewer lines of code. Also, if we want to process heavy documents for RAG application then LlamaIndex provides various custom settings such as override chunk sizes, metadata filters for exact search, prompt engineering & overriding embedding model
- **Data Used**:
Annual financial statement / life insurance documents stored in a single folder
- **Approach**:
Build a project which should solve the following requirements:
	- Users would get responses from the financial statement & the Life Insurance policy statements.
	- If they want to refer to the original page from which the bot is responding, the bot should provide a citation as well.
- **Challenges faced**: Segmentation of the document and creation of a coherent response across different documents

## Conclusions
- Appropriate results are achieved by executing queries such as 
	- What was uber revenue in 2021?
	- Which services gave uber the most revenue?
	- What was uber loss in 2021?
	- What is the Age Eligibility for Members?
	- What is the process for surrendering the policy?

## Technologies Used
- llama-index: 0.12.4
- Python: 3.10
- pandas: 2.2.2
- OpenAI: GPT 4.1
- text-embedding-ada-002 
- Chroma Vector DB

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- LlamaIndex, Pandas, Medium, Stackoverflow, OpenAI, Cohere

## Contact
Created by [@sahilavasthi] - feel free to contact me!
