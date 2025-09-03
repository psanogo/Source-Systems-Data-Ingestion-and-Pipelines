git clone https://github.com/your-repo/Source-Systems-Data-Ingestion-and-Pipelines.git
cd Source-Systems-Data-Ingestion-and-Pipelines
docker-compose up --build
python streaming_app/kafka_consumer_to_spark.py
