FROM centos/python-35-centos7
MAINTAINER Femi Osinowo "femiosinowo@gmail.com"

ENV LOGNAME=ipython
ENV USER=ipython
WORKDIR /opt/app-root/

COPY . /opt/app-root/

#RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
