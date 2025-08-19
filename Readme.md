### RAG-DB Chat using SQL

This project implements a Retrieval-Augmented Generation (RAG) system to enable conversational interaction with a database using natural language. The system translates user queries into SQL to retrieve relevant information from the database, which is then used by a large language model to generate a natural and accurate response.

**Key Features:**
* **Natural Language to SQL:** Converts user prompts into executable SQL queries.
* **Database Interaction:** Directly queries a local database (`student.db`).
* **RAG Architecture:** Integrates a RAG pipeline to enhance response accuracy and relevance.

**Project Structure:**
* `app.py`: Main application script.
* `main.py`: Core logic for the RAG system.
* `sqlite.py`: Handles database operations.
* `student.db`: The SQLite database used for the project.
* `requirements.txt`: Lists all necessary dependencies.
