FROM python:3.7
ENV PYTHONUNBUFFERED 1
RUN mkdir -p /django
WORKDIR /django
ADD . /django
RUN /usr/local/bin/python -m pip install --upgrade pip
RUN pip install -r requirements.txt
RUN chmod +x ./entrypoint.sh