FROM python:2.7.18

EXPOSE 3000

WORKDIR /app

COPY requirements.txt /app
RUN pip install -r requirements.txt

COPY application.py /app
CMD python application.py
