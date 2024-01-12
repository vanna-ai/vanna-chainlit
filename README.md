# Chainlit + Vanna

Generate SQL using AI using RAG (Retrieval-Augmented Generation)

https://github.com/vanna-ai/vanna-chainlit/assets/7146154/54a0df5b-9d2a-490c-a76b-740c87600bfe

# Install

```bash
pip install vanna
pip install chainlit
```

# Run
## Get a Vanna API Key
```python
import vanna as vn

print(vn.get_api_key('my-email@example.com'))
```

Set this as the `VANNA_API_KEY` environment variable

## Start the User Interface
```bash
chainlit run app.py
```
