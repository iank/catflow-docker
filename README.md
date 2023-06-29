# catflow-docker

docker-compose for an object recognition data pipeline 

# Setup

* Write .env and frameextractor.ini (doc TODO)
* Reverse proxy (doc TODO)

# See also

## Services

* [catflow-ingest](https://github.com/iank/catflow_ingest): Data ingestion (pipeline entry point)
* [catflow-service-videosplit](https://github.com/iank/catflow_service_videosplit): Video splitting service
* [catflow-service-inference](https://github.com/iank/catflow_service_inference): Inference service
* [catflow-service-filter](https://github.com/iank/catflow_service_filter): Vector database filtering service
* [catflow-service-taskcreator](https://github.com/iank/catflow_service_taskcreator): Label Studio task creation service

* [inference](https://github.com/iank/catflow-inference): Inference endpoint (Detect a cat in a video and return an image w/ it highlighted)


## Support

* [catflow-worker](https://github.com/iank/catflow-worker): Service framework for `catflow-service-*`
* [catflow-train](https://github.com/iank/catflow-train): Entry point for model training

## Misc

* [catflow-edge](https://github.com/iank/catflow-edge): C++ (OpenCV, ONNX) inference demo
