# syntax=docker/dockerfile:1

FROM ubuntu

RUN apt update && \
    apt install -y python3 python3-pip

WORKDIR /app

COPY . .

RUN pip3 install -r requirements.txt

CMD [ "python3", "app.py"]
