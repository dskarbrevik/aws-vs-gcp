FROM pytorch/pytorch:latest

WORKDIR /

COPY src /src

RUN pip install -r requirements.txt

CMD ["python", "/src/train.py"]

