FROM python:3.8

WORKDIR /app

COPY requirements.txt .

RUN ls -l
RUN cat requirements.txt

RUN python --version
RUN python -m pip install --no-cache-dir -r requirements.txt

COPY main.py .

CMD ["python", "main.py"]