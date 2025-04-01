FROM python:3.9

WORKDIR /app
RUN pip install django

COPY . /app

EXPOSE 8003
CMD ["python", "manage.py", "runserver", "0.0.0.0:8003"]