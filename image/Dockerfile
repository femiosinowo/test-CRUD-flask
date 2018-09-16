FROM docker.io/python:3.7
ADD . /code
WORKDIR /code

RUN pip install -r requirements.txt
USER 1001
ENTRYPOINT ["python"]
CMD ["run.py"]
