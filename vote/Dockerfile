FROM python:2.7-alpine

COPY requirements.txt app/
RUN pip install -r app/requirements.txt

COPY . app/
CMD python app/app.py