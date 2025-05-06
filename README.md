# OpenTelemetry langchain_openai.embeddings Instrumentation

<a href="https://pypi.org/project/opentelemetry-langchain-openai-embeddings/">
    <img src="https://badge.fury.io/py/opentelemetry-langchain-openai-embeddings.svg">
</a>

This library allows tracing `langchain_openai.OpenAIEmbeddings` and `langchain_openai.AzureOpenAIEmbeddings`.

## Installation

```bash
pip install opentelemetry-langchain-openai-embeddings
```

## Example usage

```python
from opentelemetry.instrumentation.langchain_openai_embeddings import LangchainOpenAIEmbeddingsInstrumentor

LangchainOpenAIEmbeddingsInstrumentor().instrument()
```
