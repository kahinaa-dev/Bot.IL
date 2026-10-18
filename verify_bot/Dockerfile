FROM python:3.13-slim

ENV PYTHONUNBUFFERED=1 DATA_DIR=/data
WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY bot.py students.py ./

CMD ["python", "bot.py"]
