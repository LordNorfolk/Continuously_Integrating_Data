# Official python image

FROM python:3.5-slim

# set workdir to /app
WORKDIR /app

# copy current directory contents to app
COPY . /app


# pip install what we need
RUN pip install --trusted-host pypi.python.org -r requirements.txt

# make port 80 available to the worlddddd

EXPOSE 80

# make an envvar
ENV NAME world

# run it
CMD ["python", "app.py"]



