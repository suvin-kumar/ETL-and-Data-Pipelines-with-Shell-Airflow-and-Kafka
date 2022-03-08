# ETL-and-Data-Pipelines-with-Shell-Airflow-and-Kafka

This project aims to de-congest the national highways by analyzing the road traffic data from different toll plazas. Each highway is operated by a different toll operator with different IT setup that use different file formats. As a vehicle passes a toll plaza, the vehicle's data like vehicle_id,vehicle_type,toll_plaza_id and timestamp are streamed to Kafka and create a data pipeline that collects the streaming data and loads it into a database.
