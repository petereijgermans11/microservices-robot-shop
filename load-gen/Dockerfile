FROM python:3

WORKDIR /load

COPY requirements.txt /load/

RUN pip install -r requirements.txt

COPY run.sh /load/
COPY robot-shop.py /load/

CMD ["./run.sh"]

