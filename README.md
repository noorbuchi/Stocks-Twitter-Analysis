# Stocks-Twitter-Analysis

This project automates the creation of AWS EC2 instances using Streamlit web
application. Additionally. it configures a cloud environment on the instance
using FastAPI to send HTTP requests. The main goal is to retrieve and graph
stock market and Twitter data using a stock ticker. This tool was created with
great help from [@enpuyou](https://github.com/enpuyou) and
[@griffinh1](https://github.com/griffinh1) in cloud computing course.

## Steps for Running:

Install pipenv:

```shell
pip install pipenv
```

Install dependencies:

```shell
pipenv install
```

Run the web application:

```shell
pipenv run streamlit run src/visualization.py
```
