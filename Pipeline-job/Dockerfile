FROM python:3.9

WORKDIR /app

# Copy everything inside the project, including the 'app' folder
COPY . /app

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "/app/app/app.py"]
