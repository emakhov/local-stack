FROM ghcr.io/mlflow/mlflow:v2.10.2

RUN pip install --no-cache-dir \
    psycopg2-binary \
    boto3 \
    pyminio

EXPOSE 5000

CMD ["mlflow", "server"]