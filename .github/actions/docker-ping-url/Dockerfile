FROM python:3.8

WORKDIR /app

COPY requirements.txt .

RUN python --version
RUN python -m pip install --no-cache-dir -r requirements.txt

COPY main.py .
CMD ["python", "/app/main.py"]