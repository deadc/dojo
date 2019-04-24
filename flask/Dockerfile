FROM python:2.7
MAINTAINER me, myself and I

WORKDIR /app

COPY requirements.txt /app
RUN pip install --requirement requirements.txt

COPY . /app

ENTRYPOINT ["python"]
CMD ["app.py"]
