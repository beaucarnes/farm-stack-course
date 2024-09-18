FROM python:3

WORKDIR /usr/src/app
COPY requirements.txt ./

RUN pip install --no-cache-dir --upgrade -r ./requirements.txt

EXPOSE 3001

CMD [ "python", "./src/server.py" ]