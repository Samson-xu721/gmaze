![Python Version](https://img.shields.io/badge/python-2.7-blue.svg)
![Code status](https://img.shields.io/badge/status-work%20in%20progress-red.svg)

# Jupyter Notebook Python, Spark, netCDF4

Add Ocean's Big Data Mining (OBIDAM) python packages to the [pyspark docker stack from Jupyter folks](https://github.com/jupyter/docker-stacks/tree/master/pyspark-notebook)

## Build the image
	docker build -t obidam:test .

## Run it
	docker run -it --rm -p 8888:8888 obidam:test
	docker run -it --rm obidam:test start.sh "conda list"
	docker run -it --rm obidam:test start.sh "cat /etc/*release
