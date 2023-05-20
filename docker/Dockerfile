FROM python:alpine3.17
COPY . /application
WORKDIR /application
COPY req.txt .
RUN pip install -r req.txt
EXPOSE 5001
CMD ["python", "app.py"]