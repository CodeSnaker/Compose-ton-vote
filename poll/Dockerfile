FROM python:3.13-slim

WORKDIR /app

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

EXPOSE 80

COPY . .

CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]