FROM ubuntu:16.04
WORKDIR '/app'

COPY . .
RUN apt-get update -y
RUN apt-get install -y python3-pip python3-dev build-essential
RUN pip3 install --upgrade pip 
RUN pip3 install -r requirements.txt
EXPOSE 5000
CMD ["python3","/app/app.py"]

