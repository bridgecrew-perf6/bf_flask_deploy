FROM python:3.8

ADD . /www
WORKDIR /www

RUN python -m pip install --upgrade pip 

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY aws /root/.aws

CMD uwsgi uwsgi.ini


