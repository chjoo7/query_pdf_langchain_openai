# Question to PDF using LangChain and OpenAI LLM

- Ask a question using Korean sentence target to large PDF files via LangChain and OpenAI API.
- Split documents using LangChain splitter or fixed chunks and store into Dataframe
- Query embedding compare cosine similarity with embedding data in Dataframe and return by similarity ranking TopN.


## Installation

clone and install the git repository:

```bash
git clone https://github.com/chjoo7/question_pdf_langchain_openai
```


## Models

EMBEDDING_MODEL = "text-embedding-ada-002"
EMBEDDING_ENCODING = 'cl100k_base'
model="gpt-3.5-turbo"


## Data

PDF data inlcudes all the regulations and rules on industry safety related Korean texts 840 pages long.