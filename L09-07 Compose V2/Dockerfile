FROM python:3.13.0a6-alpine3.19
ADD app.py requirements.txt code/
WORKDIR /code
RUN pip install -r requirements.txt
CMD ["python", "app.py"]