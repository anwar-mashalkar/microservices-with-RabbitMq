FROM python
WORKDIR /app
COPY requirements.txt .
RUN pip3 install -r requirements.txt
COPY healthcheck.py .
CMD ["python", "healthcheck.py"]
