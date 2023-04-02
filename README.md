# LangChain Data Demo

This is a [Jupyter Notebook](https://github.com/hodgesmr/LangChain-Data-Demo/blob/main/LangChain%20Data%20Demo.ipynb) that demostrates a variety of data engineering and anaysis tasks one can tackle with [LangChain](https://python.langchain.com/en/latest/index.html). It walks through using the LLM (via OpenAI) to write and execute SQL queries, and then pass the results of those queries to Python for data visualization. It uses public data voter files.

## Setup

Before you can run the [Notebook](https://github.com/hodgesmr/LangChain-Data-Demo/blob/main/LangChain%20Data%20Demo.ipynb), you need to copy [.env.example](./.env.example) to [.env](./.env) (which is ignored by git) and fill in the `OPENAI_API_KEY` environment variable.

Also, be sure to install the requirements:

```sh
pip install -r requirements.txt
```

I wrote and tested this Notebook in Python 3.10.

## License

All code is provided under the [BSD 3-Clause license](https://github.com/hodgesmr/LangChain-Data-Demo/blob/main/LICENSE).

## North Carolina Voter Data

The data used by the code in this repository originated from the North Carolina State Board of Elections, with the following [license](https://s3.amazonaws.com/dl.ncsbe.gov/data/ReadMe_PUBLIC_DATA.txt):

```
/* *******************************************************************************
* name:     ReadMe_PUBLIC_DATA.txt
* purpose:  Notification to the public, media, and interested parties.  
*           The data and documents contained within this publicly accessible site 
*           and all subforders herein provided by the NC State Board of Elections 
*           are considered public information per NC General Statutes. 
* URL:      https://dl.ncsbe.gov/list.html
* updated:  09/16/2020
******************************************************************************* */

Citations:

Â§ 132-1. Public Records.
https://www.ncleg.gov/EnactedLegislation/Statutes/PDF/BySection/Chapter_132/GS_132-1.pdf

Â§ 163-82.10.  Official record of voter registration.
https://www.ncleg.gov/EnactedLegislation/Statutes/PDF/BySection/Chapter_163/GS_163-82.10.pdf
```

## A Matt Hodges project

This project is maintained by [@MattHodges](https://mastodon.social/@MattHodges).

_Please use it for good, not evil._
