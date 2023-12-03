FROM python:3.8.16

COPY . /app

RUN pip3 install flask 

RUN chmod +x /app/App.py

WORKDIR /app

CMD ["python3","App.py"]