FROM ubuntu:20.04

RUN apt update && apt install python3 -y && apt install python3-pip -y

RUN pip3 install flask

COPY . .

CMD ["python3", "app.py"]
