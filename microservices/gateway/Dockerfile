FROM  python:3.9.18-slim
    
COPY ./app.py .
COPY ./urls.py .
COPY ./requirements.txt .
RUN pip install -r requirements.txt

EXPOSE 8082
CMD ["flask", "run", "--host=0.0.0.0", "--port=8082"]