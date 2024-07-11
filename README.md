# answer-me-tolkien

This is a simple RAG application built using langchain and chroma database.

1. Store the API key in the `.env` file.

2. Create a database

```bash
python create_db.py
```

3. Or update the database

```bash
python update_db.py
```

4. Query the llm with context from the vector db

```python
python query_db.py "what happened to gandalf that turned him white?"
```

I have used cohere's embedding and the chat models.

> [!NOTE]
> If you want to run models locally, use Ollama

I have used lotr books as the source data.

![output](assets/output.png)
