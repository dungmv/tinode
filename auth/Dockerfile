FROM python:3.7-alpine

WORKDIR /app

COPY requirements.txt dummy_data.json auth.py /app/

RUN pip install -r requirements.txt

EXPOSE 5000

CMD [ "python", "auth.py" ]
