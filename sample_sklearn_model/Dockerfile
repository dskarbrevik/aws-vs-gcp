FROM --platform=linux/amd64 python:3.11

WORKDIR /

COPY src /src

RUN pip install -r /src/requirements.txt

CMD ["python", "/src/train.py"]