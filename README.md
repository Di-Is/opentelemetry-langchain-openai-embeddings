# OpenTelemetry OpenAI Instrumentation

<a href="https://pypi.org/project/opentelemetry-langchain-openai-embeddings/">
    <img src="https://badge.fury.io/py/opentelemetry-langchain-openai-embeddings.svg">
</a>

This library allows tracing OpenAI prompts and completions sent with the official [OpenAI library](https://github.com/openai/openai-python).

## Installation

```bash
pip install opentelemetry-langchain-openai-embeddings
```

## Example usage

```python
from opentelemetry.instrumentation.langchain_openai_embeddings import LangchainOpenAIEmbeddingsInstrumentor

LangchainOpenAIEmbeddingsInstrumentor().instrument()
```
