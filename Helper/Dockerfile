FROM python:3.11

ENV APP_HOME /app

WORKDIR .

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5000

ENTRYPOINT ["python", "setup.py"]
