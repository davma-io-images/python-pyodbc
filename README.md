## 1. Introduction

Python official images with pyodbc == 4.0.30

[![Build and push images](https://github.com/davma-io-images/python-pyodbc/actions/workflows/docker-image.yml/badge.svg)](https://github.com/davma-io-images/python-pyodbc/actions/workflows/docker-image.yml)

## 2. Requirements

1. [Docker](https://docs.docker.com/get-docker/)

## 3. Docker pull

You can download the full image from [Docker Hub](https://hub.docker.com/) with the following command.


````
#python3.11
docker pull davma/python-pyodbc:3.11
````
````
#python3.10
docker pull davma/python-pyodbc:latest
````
````
#python3.9
docker pull davma/python-pyodbc:3.9
````
````
#python3.8
docker pull davma/python-pyodbc:3.8
````
````
#python3.7
docker pull davma/python-pyodbc:3.7
````

## 4. Image build

You can run the image build with the following commands

````
git clone https://github.com/davma-io-images/python-pyodbc.git
cd python-pyodbc
docker build -t python-pyodbc .
````

## 5.Documentation and guides

[pyodbc](https://pypi.org/project/pyodbc/)

[Microsoft ODBC 17](https://docs.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-2017)
