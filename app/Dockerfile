FROM python:3.12-slim-bookworm
COPY ./requirements.txt /app/requirements.txt
WORKDIR .
#RUN pip install -r requirements.txt
COPY app.py .
EXPOSE 5000
CMD ["python", "app.py" ]


