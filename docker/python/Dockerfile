FROM python:3.6
MAINTAINER anton@localhost

COPY ./father_app_v1 /father_app_v1

WORKDIR /father_app_v1

RUN pip install -r requirements.txt

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000" ]