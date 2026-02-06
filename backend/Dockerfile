# Base image
FROM python:3.12-slim

# set work directory
WORKDIR /app

# copy requirement file
COPY requirements.txt .

# install dependancies 
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# run backend
CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "8000"]