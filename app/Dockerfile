FROM python:2.7.18

EXPOSE 3000

WORKDIR /2d54d89f7c20f90a487e833ac6695aa9

COPY requirements.txt /2d54d89f7c20f90a487e833ac6695aa9
RUN pip install -r requirements.txt

COPY application.py /2d54d89f7c20f90a487e833ac6695aa9
CMD python application.py