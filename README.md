# LangChain Data Demo

This is a [Jupyter Notebook](https://github.com/hodgesmr/LangChain-Data-Demo/blob/main/LangChain%20Data%20Demo.ipynb) that demostrates a variety of data engineering and anaysis tasks one can tackle with [LangChain](https://python.langchain.com/en/latest/index.html). It walks through using the LLM to write and execute SQL queries, and then pass the results of those queries to Python for data visualization.

## Setup

Before you can run the [Notebook](https://github.com/hodgesmr/LangChain-Data-Demo/blob/main/LangChain%20Data%20Demo.ipynb), you need to copy [.env.example](./.env.example) to [.env](./.env) (which is ignored by git) and fill in the `OPENAI_API_KEY` environment variable.

Also, be sure to install the requirements:

```sh
pip install -r requirements.txt
```

I wrote and tested this Notebook in Python 3.10.

## License

All code is provided under the [BSD 3-Clause license](https://github.com/hodgesmr/LangChain-Data-Demo/blob/main/LICENSE).

## A Matt Hodges project

This project is maintained by [@hodgesmr](https://mastodon.social/@MattHodges).

_Please use it for good, not evil._