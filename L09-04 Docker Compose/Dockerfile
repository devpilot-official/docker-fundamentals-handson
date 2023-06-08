FROM python:3-alpine3.18
ADD app.py requirements.txt code/
WORKDIR /code
RUN pip install -r requirements.txt
CMD ["python", "app.py"]