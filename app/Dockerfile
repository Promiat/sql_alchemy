FROM python:3.6
WORKDIR /app
COPY . /app/

RUN pip3 install --requirement ./requirements.txt
EXPOSE 5000
ENTRYPOINT FLASK_APP=app.py flask run --host=0.0.0.0
CMD ["run", "--host", "0.0.0.0"]