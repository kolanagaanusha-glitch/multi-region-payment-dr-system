FROM python:3.13-slim

WORKDIR /app

COPY application/ .

RUN pip install -r requirements.txt

EXPOSE 5000

CMD [name: Payment System CI

on:
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout Code
      uses: actions/checkout@v4

    - name: Setup Python
      uses: actions/setup-python@v5
      with:
        python-version: '3.13'

    - name: Install Dependencies
      run: |
        cd application
        pip install -r requirements.txt

    - name: Run Application Test
      run: |
        cd application
        python -m py_compile app.py"python", "app.py"]