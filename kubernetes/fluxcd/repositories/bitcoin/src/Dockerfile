FROM python:3.8-slim
WORKDIR /app
COPY requirements.txt /app
RUN pip install --no-cache-dir -r requirements.txt
COPY . /app
EXPOSE 8080
CMD ["streamlit", "run", "main.py", "--server.port", "8080"]
