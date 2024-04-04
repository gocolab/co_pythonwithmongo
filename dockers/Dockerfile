FROM python:3.11

# 작업 디렉토리 설정
WORKDIR /app

# Git repository clone
RUN git clone -b complets https://github.com/gocolab/co_pythonwithmongo co_pythonwithmongo_complets

RUN git clone -b debugs https://github.com/gocolab/co_pythonwithmongo

WORKDIR /app/co_pythonwithmongo

RUN pip install -r ./requirements.txt

RUN rm -rf .git

