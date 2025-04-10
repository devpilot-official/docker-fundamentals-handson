FROM python:3.13.3-alpine3.21
ADD app.py requirements.txt code/
WORKDIR /code
RUN pip install -r requirements.txt
CMD ["python", "app.py"]