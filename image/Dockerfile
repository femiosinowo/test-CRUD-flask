FROM ubuntu:16.04
MAINTAINER Rajdeep Dua "dua_rajdeep@yahoo.com"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
ENV LOGNAME=ipython
ENV USER=ipython

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["run.py"]
