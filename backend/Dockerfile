FROM python:3.8-slim-buster
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
COPY . .
EXPOSE 5000
ENV AWS_DEFAULT_REGION="us-east-1"
CMD [ "python3", "app.py"]
