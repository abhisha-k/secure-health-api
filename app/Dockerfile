FROM python:3.11-slim
WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
<<<<<<< HEAD
=======
RUN pip install pytest pytest-cov
>>>>>>> 5b37c7e (Initial commit)
COPY . .
EXPOSE 8443
CMD ["python","server.py"]