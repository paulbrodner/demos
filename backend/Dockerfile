FROM python:3.7-alpine 

WORKDIR /app 
COPY requirements.txt /app
COPY main.py /app/main.py 
RUN pip3 install -r requirements.txt 

ENTRYPOINT ["python3"] 
CMD ["/app/main.py"]
