FROM python:3.5-alpine

COPY . /application

WORKDIR /application

RUN pip install -r requirements.txt

EXPOSE 8001

CMD ["python", "python-flask-api.py"]
