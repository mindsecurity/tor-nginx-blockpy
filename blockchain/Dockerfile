FROM python:3.6-alpine

ADD blockchain.py requirements.txt config.ini /code/

WORKDIR /code

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "blockchain.py"]
