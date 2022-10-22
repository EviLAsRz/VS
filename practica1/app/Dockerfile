FROM ubuntu:latest
COPY . .
RUN apt-get  update -y
RUN apt install python3 -y
RUN apt install python3-pip -y
RUN apt install -y default-libmysqlclient-dev
RUN apt install mariadb-client -y
RUN pip install -r requirements.txt
CMD python3 web_project/manage.py runserver 0.0.0.0:8800
