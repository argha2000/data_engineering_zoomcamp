FROM python:3.12

RUN pip install pandas, numpy ,pyarrow,polars,jupyter,sqlalchemy,psycopg2-binary

WORKDIR /app
COPY pipeline.py pipeline.py

ENTRYPOINT [ "python", "pipeline.py" ]