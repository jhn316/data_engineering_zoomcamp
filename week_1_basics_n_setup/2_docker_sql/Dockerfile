FROM python:3.10

RUN pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org pip pandas sqlalchemy psycopg2

WORKDIR /app
COPY pipeline.py pipeline.py

ENTRYPOINT [ "python", "pipeline.py" ]