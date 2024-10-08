# Chatbot using langchain and ollama (open source llm like llama, gema etc)

## Create venv 
Using python 3.11.5

```
python -m venv yourenv
```

activate

```sh
# for mac
source yourenv/bin/activate

# for windows
yourenv\Scripts\activate
```

## Download Ollama and LLM on your Local
https://ollama.com/

```sh
# sample install gemma2 with 2 billion size
ollama run gemma2:2b

```

## Setup Langmith tracking (OPTIONAL)
```
LANGCHAIN_API_KEY="your_langchain_key"
LANGCHAIN_PROJECT="chatbot-llama"
```
```
# os.environ["LANGCHAIN_TRACING_V2"] = "true"
# os.environ["LANGCHAIN_API_KEY"] = f"{os.getenv('LANGCHAIN_API_KEY')}"
```
