## Chat with SQL and Tabular Data Using Azure OpenAI API

### Overview
This project leverages the power of the OpenAI API and Azure OpenAI to enable conversational interaction with SQL databases and tabular data such as CSV and Excel files. It integrates Retrieval-Augmented Generation (RAG) techniques to facilitate seamless conversations with datasets. The frontend is built using Gradio, providing an intuitive and user-friendly interface.

### Features
- **Conversational SQL Querying**: Utilize Langchain SQL agents to generate, execute, and explain SQL queries through natural language interactions.
- **Tabular Data Interaction**: Chat with data stored in CSV and Excel files, making data analysis accessible and straightforward.
- **RAG Integration**: Convert datasets into vectors using OpenAI embeddings to enhance conversational capabilities and provide accurate responses.
- **User-Friendly Interface**: Gradio-based frontend for easy interaction and visualization.

### Libraries Used
- **gradio**: For building the frontend interface.
- **langchain**: To facilitate communication between the LLM and the SQL agent.
- **langchain_community**: Community-driven extensions and integrations for Langchain.
- **langchain_core**: Core components for building advanced LLM applications.
- **pandas**: Data manipulation and analysis.
- **pyprojroot**: Project root path management.
- **python-dotenv**: Managing environment variables.
- **PyYAML**: YAML file parsing and handling.
- **SQLAlchemy**: SQL toolkit and Object-Relational Mapping (ORM).
- **openai**: Access to OpenAI's powerful language models.

### How It Works
1. **SQL Query Generation**: The Langchain SQL agent interacts with the LLM to generate SQL queries based on user input.
2. **Query Execution**: Generated SQL queries are executed against the connected database.
3. **Result Explanation**: The output of the SQL queries is explained using the LLM to provide understandable insights.
4. **Conversational Data Interaction**: RAG techniques are used to convert datasets into vectors, enabling detailed and accurate responses to user queries.

