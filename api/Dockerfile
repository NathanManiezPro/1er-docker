FROM python:3

WORKDIR /app

COPY requirements.txt ./
RUN pip install -r requirements.txt
EXPOSE 5000

COPY . .

CMD ["python", "-m", "flask", "run", "--host=0.0.0.0"]