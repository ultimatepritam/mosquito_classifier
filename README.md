# Mosquito classifier (Aedes, Anopheles, Culex) 
Researcher can use this classifier to automatically distinguish a particular type of mosquito from a large dataset

![el](mosq/aedes/pic_012.jpg)
![el](mosq/anopheles/pic_053.jpg)
![el](mosq/culex/pic_017.jpg)

# Requirements

* [docker](https://www.docker.com/products/docker-toolbox)
* [tensorflow](https://www.tensorflow.org/install)
* [python](https://www.python.org/downloads)
* [numpy](https://pypi.python.org/pypi/numpy)

# Usage 

1. Start the docker image `docker run -it -v ~/mosquito_classifier/:/mosquito_classifier/ gcr.io/tensorflow/tensorflow:latest-devel`

2. Run the mosq script to label the image `python /mosquito_classifier/mosq.py <path_to_file>`

# Results

