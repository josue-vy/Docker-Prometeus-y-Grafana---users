FROM python:3.9

COPY . /usr/src/app
WORKDIR /usr/src/app

RUN python3 -m pip install -r requeriments.txt

CMD ["uvicorn", "app:app", "--proxy-headers", "--host", "0.0.0.0"]