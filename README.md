# AI Engineering: Retrieval Augmented Generation (RAG) for LLMs

Code for Zero To Mastery [AI Engineering: Retrieval Augmented Generation (RAG) for LLMs](https://zerotomastery.io/courses/ai-engineer-bootcamp-retrieval-augmented-generation/) course

### Setup

Copy `example.env` to `.env` and paste in OpenAI key.

```sh
python3.13 -m venv venv
source venv/bin/activate
python -m pip install -U openai python-dotenv jupyter pdf2image numpy faiss-cpu

# Install poppler to work with pdf2image

sudo apt-get install poppler-utils # Linux
brew install poppler # macOS

jupyter lab
```
