FROM python:3.9

WORKDIR /app

COPY ./requirements.txt .

RUN pip3 install --no-cache-dir -r ./requirements.txt

COPY ./run.py .

CMD [ "python", "run.py"]