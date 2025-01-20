FROM python:3.12

RUN apt-get install wget
RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app
COPY ingest_data_taxi.py ingest_data_taxi.py
COPY ingest_data_zone.py ingest_data_zone.py 

ENTRYPOINT [ "python", "ingest_data_zone.py"]