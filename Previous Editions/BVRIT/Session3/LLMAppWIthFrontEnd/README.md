# Combining ollama + langchain + streamlit to Build your own ChatPDF and run them locally
Reference - [vndee's repo](https://github.com/vndee/local-rag-example)

Dependencies:
- langchain
- streamlit
- streamlit-chat
- pypdf
- chromadb

```bash
pip install langchain streamlit streamlit_chat chromadb pypdf fastembed
```

- Ensure ollama's APIs are working - ```ollama serve``` | ```sudo ollama serve```.

- Ensure that whichever model is being used to run the app is downloaded, else run ```ollama pull <model_name>. model_name can be found in [rag.py script](rag.py) in ```ChatPDF``` class defination. 

