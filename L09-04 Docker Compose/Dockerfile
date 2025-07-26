FROM python:3.14.0rc1-alpine3.22
ADD app.py requirements.txt code/
WORKDIR /code
RUN pip install -r requirements.txt
CMD ["python", "app.py"]