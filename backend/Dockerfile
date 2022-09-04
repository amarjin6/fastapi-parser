FROM python:3
ENV PYTHONUNBUFFERED=1
ENV PYTHONDONTWRITEBYTECODE=1
WORKDIR /app
COPY . .
RUN pip install --no-cache-dir --upgrade -r requirements.txt
