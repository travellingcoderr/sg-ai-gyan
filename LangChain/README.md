***Langchain Overview: Components and Workflow***

Langchain enables the creation of generative AI applications by orchestrating large language models (LLMs) with tools, prompts, and integrations. The framework's workflow centers on three main components:

1. **Retrieving Data**: This involves using document loaders to access diverse sources of information.
2. **Text Chunking**: Due to LLM context window limitations, text is split into manageable chunks.
3. **Storing Chunks**: These chunks are stored as vector embeddings in vector databases for efficient semantic search.

Proper data parsing, chunking, and storage underpin the accuracy and effectiveness of AI-powered assistants and applications built with Langchain.

### Sequential Execution and Chaining in Langchain

Langchain employs a sequential, directed acyclic graph (DAG) structure where each task executes in order without backward movement. Application logic is constructed through chaining, combining prompts, LLMs, and context from vector databases, with optional use of persistent memory and multiple LLMs. This approach ensures predictable, stepwise execution and is foundational for building reliable generative AI workflows within Langchain.

# Langraph Overview: Agentic Applications and Graph-Based Workflows

Langraph supports the development of stateful, multi-agent AI systems where multiple agents, each represented as nodes, collaborate and communicate to solve complex workflows. Unlike Langchain's sequential model, Langraph leverages graph structures with nodes, edges, and shared persistent memory, allowing for dynamic, non-linear execution, feedback loops, and even human-in-the-loop mechanisms. This flexibility enables modeling of intricate processes such as software development life cycles and other multi-step, collaborative tasks.

# Comparing Traditional RAG and Agentic RAG Approaches

Traditional Retrieval-Augmented Generation (RAG) systems rely on LLMs interacting directly with a retrieval database to provide context for outputs, forming a straightforward pipeline. 

Agentic RAG introduces AI agents that autonomously decide when to access databases, invoke tools, or take other actions, creating more adaptive and intelligent workflows. This shift enables more dynamic decision-making and complex task handling beyond simple information retrieval.
