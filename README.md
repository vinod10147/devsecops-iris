# Dev-Sec-Ops Demo/Assignment

[![codecov](https://codecov.io/gh/PGCSEDS-IIITH/devsecops-iris/branch/master/graph/badge.svg?token=EILEH8L7R5)](https://codecov.io/gh/PGCSEDS-IIITH/devsecops-iris)

This repository contains code which demonstrates Dev-Sec-Ops using a `FastAPI` application which predicts the flower class using the IRIS dataset (https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)

## Running Instructions
- Create a fork of the repo using the `fork` button.
- Clone your fork using `git clone https://www.github.com/<your-username>/mlops-iris.git`
- Install dependencies using `pip3 install -r requirements.txt`
- Run application using `python3 main.py`
- Run tests using `pytest`

## CI/CD
- `unittest`: Run the python unit tests using pytest
- `codecoverage`: Analyze code quality using codecov and upload results
- `container-security`: Scan docker image using anchore and upload SARIF report artifact
- `upload_zip`: Package code and upload as artifact


## Assignment Tasks
