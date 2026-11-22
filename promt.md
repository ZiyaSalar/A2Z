# Prompt: Create a 17-Slide Generative AI Training Learning Presentation

Act as an expert corporate presentation designer and Generative AI technical trainer.

Create a professional PowerPoint presentation explaining the technical concepts and technologies I learned during my Generative AI training program.

## 1. Strict presentation requirements

- Create exactly **17 content slides**.
- Do NOT create an introduction/title slide.
- Do NOT create a thank-you or closing slide.
- I will add these slides myself.
- I will provide a company PowerPoint template. **You must strictly follow the provided company template.**
- Do not modify the company branding, theme, master layouts, logo, fonts, colors, headers, footers, or existing design language.
- Use the existing layouts and placeholders wherever possible.
- Do not introduce a new visual theme.
- Maintain consistent formatting across all slides.
- Keep content concise, technical, and suitable for a corporate audience.
- Avoid overcrowding slides with paragraphs.
- Use architecture diagrams, flowcharts, tables, and visual representations wherever they improve understanding.
- Use technically accurate terminology.
- Do not invent projects, implementation experience, or achievements that are not mentioned in the supplied syllabus.

## 2. Slide-by-slide content

### Slide 1 – Python Fundamentals and FastAPI
Cover:
- Python fundamentals and core programming concepts.
- Functions, modules, packages, and exception handling.
- Introduction to FastAPI.
- Creating REST API endpoints.
- Request validation using Pydantic.
- Asynchronous programming.

Visual suggestion: Show a simple FastAPI request-response architecture.

### Slide 2 – Python for Data Science: NumPy and Pandas
Cover:
- NumPy arrays and array manipulation.
- Indexing, slicing, vectorization, and broadcasting.
- Statistical operations.
- Pandas Series and DataFrames.
- Data filtering, selection, and indexing.
- Handling missing data.
- Merging, joining, and concatenating DataFrames.

Visual suggestion: Show a simple data analysis workflow using NumPy and Pandas.

### Slide 3 – .NET and C# Fundamentals
Cover:
- C# syntax, variables, data types, and operators.
- Control structures and loops.
- Interfaces, delegates, and events.
- Generics and exception handling.
- Collections: Lists, Arrays, and Dictionaries.
- LINQ.
- Asynchronous programming using async and await.
- File handling and JSON/XML serialization.

Keep this slide concise. Focus on the important development concepts.

### Slide 4 – Design Patterns and Dependency Injection
Cover:
- Factory Method design pattern.
- Purpose of the Factory Method.
- Abstract classes and interfaces.
- Dependency Injection and its importance.
- Constructor, method, and property injection.
- Built-in DI container in .NET Core.
- ServiceCollection and ServiceProvider.
- Transient, Scoped, and Singleton lifetimes.

Visual suggestion: Illustrate how a client obtains an object through a factory and how dependency injection supplies dependencies.

### Slide 5 – Introduction to Large Language Models
Cover:
- What are Large Language Models (LLMs)?
- Evolution and importance of LLMs.
- Applications of LLMs.
- Text generation, summarization, translation, sentiment analysis, and conversational AI.
- Popular model examples such as GPT and BERT.

Visual suggestion: Show a central LLM connected to different real-world applications.

### Slide 6 – Transformer Architecture
Explain the Transformer architecture:
- Evolution from RNNs and LSTMs.
- Self-attention mechanism.
- Multi-head attention.
- Positional encoding.
- Encoder and decoder.
- Transformer layers.
- End-to-end training.

Visual suggestion: Include a clear Transformer architecture diagram showing input embeddings, positional encoding, encoder, decoder, and output. Make the diagram technically accurate.

### Slide 7 – Pre-trained Models and Fine-tuning
Cover:
- What are pre-trained models?
- GPT and BERT.
- Differences between their architectures and applications.
- Training datasets and methodologies.
- Hugging Face Transformers library.
- Text generation using GPT.
- Text classification using BERT.
- Transfer learning and fine-tuning.
- Domain-specific model adaptation.

Visual suggestion: Show the workflow:
Pre-trained Model → Fine-tuning with Custom Dataset → Task-specific Model → Prediction.

### Slide 8 – Building Applications with LLMs
Cover:
- NLP tasks using LLMs.
- Text classification.
- Text summarization.
- Language translation.
- Implementing NLP workflows.
- Integrating LLMs into existing applications.
- Real-world applications.

Visual suggestion: Show an application architecture where a user request is processed by an application, sent to an LLM, and returned as a response.

### Slide 9 – Chatbots and Conversational AI
Cover:
- Chatbot design principles.
- Building chatbots using LLM frameworks.
- User experience and interface design.
- Handling user inputs and generating responses.
- Maintaining conversation context.
- Managing conversation flow.
- Integrating LLMs with existing systems.

Visual suggestion: Show a chatbot conversation flow, including user input, context management, LLM processing, and response generation.

### Slide 10 – Responsible and Ethical AI
Cover:
- Bias and fairness in LLMs.
- Bias detection and mitigation.
- Data privacy and security.
- Regulatory compliance.
- Secure data handling and storage.
- Model evaluation and performance metrics.
- Deployment, monitoring, and maintenance.
- Human oversight in AI systems.

Visual suggestion: Use a clean framework showing Responsible AI pillars: Fairness, Privacy, Security, Transparency, and Human Oversight.

### Slide 11 – Introduction to Azure AI
Cover:
- Overview of Azure AI services.
- Azure Machine Learning.
- AI-powered APIs and tools.
- Basic machine learning concepts.
- Machine learning workflows.
- Azure Machine Learning Studio.
- Model creation and deployment.

Visual suggestion: Show the basic lifecycle of an ML model: Data → Training → Evaluation → Deployment.

### Slide 12 – Prompt Engineering
Cover:
- Introduction to prompt engineering.
- Designing effective prompts.
- Prompt structuring for code generation.
- Debugging and code optimization.
- GitHub Copilot and agentic mode.
- Generating code snippets and documentation.
- Generating test cases and automated testing scripts.
- Language-specific prompting.
- Reducing hallucinations.
- System prompts and guardrails.
- Human-in-the-loop approach.

Visual suggestion: Show the relationship between User Prompt, LLM, Generated Output, Evaluation, and Improved Prompt.

### Slide 13 – Azure AI Foundry
Cover:
- Introduction to Azure AI Foundry.
- AI Foundry workspace.
- Model selection and deployment.
- Deploying models as REST endpoints.
- Model fine-tuning.
- Performance monitoring.

Visual suggestion: Show the workflow:
AI Foundry Workspace → Model Selection → Model Deployment → REST API Endpoint → Application Integration.

Use the current official Azure product terminology where appropriate.

### Slide 14 – Azure AI Search
Cover:
- Introduction to Azure AI Search.
- Search service and data sources.
- Indexes and index fields.
- Uploading and indexing documents.
- Cognitive skills.
- OCR, entity recognition, and sentiment analysis.
- Semantic search.

Visual suggestion: Explain the flow:
Documents → Data Source → Indexing → Search Index → User Query → Search Results.

### Slide 15 – Generative AI Architecture and Azure Integration
Cover:
- Generative AI application architecture.
- GenAI architecture patterns.
- Plugin patterns.
- Modular and scalable AI applications.
- Integrating Azure AI services with applications.
- Using Azure AI tools for ML and NLP.
- End-to-end chatbot architecture and deployment.

Visual suggestion: Create an end-to-end architecture showing:
Frontend → Backend/API → Azure AI Services/LLM → Response → Frontend.

Clearly identify the role of each component.

### Slide 16 – MCP and Agentic Tool Calling
Cover two related concepts.

**Part A: Agentic Tool Calling**
- Function calling and tool calling.
- Defining tools and JSON schemas.
- Structured outputs.
- Tool selection and invocation.
- Handling tool results.
- Multi-step reasoning and agent loops.
- ReAct pattern.
- Azure AI Agent Service.
- Semantic Kernel and LangChain.

**Part B: Model Context Protocol (MCP)**
- What is MCP and why it is needed?
- MCP architecture.
- Hosts, clients, and servers.
- Connecting LLMs to external tools and data.
- Building and configuring MCP servers.
- Consuming MCP servers from AI agents.

Visual suggestion: Show an LLM agent connected to an MCP client, MCP server, and external tools/data sources. Clearly explain the flow of a tool call.

### Slide 17 – Retrieval-Augmented Generation (RAG)
Cover:
- What is RAG and why is it needed?
- Embeddings and vector representations.
- Vector databases.
- Azure AI Search as a vector store.
- Document chunking.
- Indexing and similarity search.
- RAG architecture and workflow.
- Grounding LLM responses with retrieved context.
- Integration of Azure AI Search with Azure OpenAI.
- Advanced RAG: Hybrid Search, Reranking, and Query Rewriting.
- Agentic RAG.
- Evaluating relevance and reducing hallucinations.
- Monitoring and improving RAG pipelines.

Visual suggestion: Include an end-to-end RAG architecture:

User Query → Embedding Generation → Vector/Search Retrieval → Relevant Context → LLM → Grounded Response.

Also show how MCP tools can be integrated with an agent to query Azure AI Search.

## 3. Design and presentation quality

Follow these instructions throughout the presentation:

1. Preserve the company PPT template without any modifications to its branding or theme.
2. Use diagrams instead of lengthy textual explanations wherever possible.
3. Use a consistent visual style and professional technical terminology.
4. Use appropriate Azure service icons and architecture diagrams.
5. Highlight important keywords and technologies.
6. Avoid unnecessary animations and decorative elements.
7. Maintain sufficient whitespace and readable font sizes.
8. Keep each slide focused on one major topic.
9. Use short explanations rather than copying entire syllabus descriptions.
10. Ensure all architecture diagrams have clear labels and directional arrows.

## 4. Final output

Generate an editable PowerPoint (.pptx) containing exactly 17 content slides.

The presentation should look like a professional corporate technical-learning presentation, not a classroom lecture or a copied syllabus.

The company template is the highest-priority design constraint. Do not violate it under any circumstances.