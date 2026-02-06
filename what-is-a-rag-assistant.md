# What is a Rag Assistant?


Large Language Models (LLMs) are a form of artificial intelligence that understand and generate human language. They are trained on large amounts of text, which allows them to answer questions, explain concepts, summarise content, and produce clear, natural-sounding responses. On their own, LLMs are 
- strong generalists
- knowledge is fixed at the time they were trained and 
- they have no built-in understanding of an organisation's specific information.

Retrieval-Augmented Generation (RAG) extends LLMs by letting them look up information at the moment a question is asked, it in grounds answers in current, authoritative information from trusted sources, not relying only on past training.

With RAG, LLMs can use an organisation's institutional knowledge — including documents, diagrams, and even information extracted from videos — to produce accurate, context-aware responses. The combination turns a generic language model into a practical, reliable assistant that explains information clearly while staying aligned with up-to-date business knowledge.

With RAG, AI can:
- Answer questions about your documents
- Summarise long content accurately
- Compare policies or versions
- Explain complex material in plain language
- Respond consistently across teams
- Cite sources (where required)

All without changing the underlying AI model.
> RAG turns generative AI from a clever writer into a reliable assistant

#What have we built?

![Alt Text](/AIResearchAssistantModel.png)

We have built an AI Assistant that
* provide a GDS compliant user interface to interact with larrge language models (link to models and research)
    * Interface to draft and submit promots to the LLM
    * Records the conversation history (context)
    * Retrieves knowledge from the knowledge base
    * Consiolidates conversation history, knowledge, system and user prompts then submits to LLM to generate an answer 
* Paved road to deploy components to CDP Platform
    * Build the knowledge base to hold DEFRA & ALB institutional knowledge
    * The Natural Language Retriever that takes a user prompt and finds document sections that are relevant to the question being asked
    * The AI Assistant fron and backends 
a prototype to provide a paved road for deploying the technology stack to deliver a generative AI solution over DEFRA & ALB specific documents.
