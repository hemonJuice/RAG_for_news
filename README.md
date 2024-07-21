# RAG_for_news
Retrieval-Augmented Generation (RAG) is the process of optimizing the output of a large language model, so it references an authoritative knowledge base outside of its training data sources before generating a response. Large Language Models (LLMs) are trained on vast volumes of data and use billions of parameters to generate original output for tasks like answering questions, translating languages, and completing sentences. RAG extends the already powerful capabilities of LLMs to specific domains or an organization's internal knowledge base, all without the need to retrain the model. It is a cost-effective approach to improving LLM output so it remains relevant, accurate, and useful in various contexts.

RAG allows developers to provide the latest research, statistics, or news to the generative models. They can use RAG to connect the LLM directly to live social media feeds, news sites, or other frequently-updated information sources. The LLM can then provide the latest information to the users.
<img width="827" alt="截屏2024-07-21 下午4 01 29" src="https://github.com/user-attachments/assets/60e53adf-2e4b-40e4-bd32-c207bb529141">

The goal of the project is to build real-time news RAG chatbot, The following are some key features we want to achieve:

1. Design a reusable RAG framework, each part can be flexibly replaced or updated.
2. The key to this RAG is to get insights from the latest news automatically instead of letting us read all of them.
3. Choose an appropriate database that can be used to store daily news, ideally should be cumulative instead of replaced every day.
4. Optimize the storage of the database instead of storing all of the information.
5. Design queries to search for relevant information in the database (information retrieval). Use more advanced techniques instead of just TF-IDF.
6. Design and optimize Prompts that are used as inputs of LLM.
7. Choose an appropriate LLM, and fine-tune it using advanced techniques (e.g. LORA, AdaLORA...). We can keep this one simple in the initial stage.
8. Design an appropriate output format, using visualization techniques.
9. Automate the whole process and integrate it into the system (cronjob...).






Reference:
https://aws.amazon.com/what-is/retrieval-augmented-generation/?nc1=h_ls
