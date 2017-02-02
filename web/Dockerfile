# setup tensorflow image context
FROM gcr.io/tensorflow/tensorflow:latest

# install dependencies
RUN pip install --upgrade pip
RUN pip install flask
RUN pip install gunicorn
RUN pip install tornado
RUN pip install Pillow

# setup app within docker container
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
ADD . /usr/src/app