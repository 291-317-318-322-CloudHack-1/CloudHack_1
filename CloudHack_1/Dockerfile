# use the `mongo` image
# copy the app directory and any files needed for your implementation from your local to the container
# equip it with all the packages and installs needed to run the flask app (packages are defined in app/requirements.txt. `pip install -r app/requirements.txt`)
# expose the port flask app will run on

From mongo-express
FROM mongo
FROM python

COPY . /app
WORKDIR /app
RUN pip install -r app/requirements.txt
EXPOSE 5001
CMD [ "python3","app/app.py"]



# ENTRYPOINT [ "python" ]
# CMD [ "demo.py" ]
# FROM python:3.8-slim-buster
# WORKDIR /app
# COPY . .
# CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]