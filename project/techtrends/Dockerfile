FROM python:3.8
LABEL maintainer="Rashmi"
EXPOSE 3111

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt && python3 init_db.py

# command to run on container start
CMD [ "python3", "app.py" ]
