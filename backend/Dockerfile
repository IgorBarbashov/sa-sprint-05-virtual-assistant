FROM python:3.10-slim

EXPOSE 5005

WORKDIR /usr/app

COPY . .

RUN pip install -r requirements.txt
RUN rasa train

CMD rasa run --enable-api --cors "*"