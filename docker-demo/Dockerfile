

# DockerFile, Image, Container

# bring the baseImage from the docker hub.
FROM python:3.9

# the image is made up the following file and the destination
ADD hello_world.py .

# dependencies
RUN pip install numpy

CMD ["python", "./hello_world.py"]
