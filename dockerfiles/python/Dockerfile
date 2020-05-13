FROM python
MAINTAINER Nikita Sharaev aka Moon1705

WORKDIR /app

COPY ./requirements.txt requirements.txt
RUN pip3 install --no-cache-dir -r requirements.txt && \
  rm -f requirements.txt

RUN django-admin startproject project . && \ 
  python3 manage.py makemigrations && \
  python3 manage.py migrate

EXPOSE 8000

CMD ["gunicorn", "project.wsgi", "-b 0.0.0.0:8000"]
