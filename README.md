# PANDAS WEB SCRAPING TOOL

This is a tool that fetches tables inside a html page and stores them into pandas

please provide the target url in the .env file
also the index of the table that you want need to be provided there


## Conda env

create:
`conda create -n pandas_web_scrape pip -y`

activate:
`conda activate pandas_web_scrape`

install:
`pip install -r requirements.txt`

## Excel export
The functionality to export the table to a Excel document has been added
the default directory for ouput is "out" and is ignored by .gitignore file by default