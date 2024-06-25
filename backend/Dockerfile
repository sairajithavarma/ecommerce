# Use an official Python runtime
FROM python:3.8-slim

# Set working directory
WORKDIR /app

# Install dependencies
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

# Copy the rest of the application
COPY . .

# Expose port 5000
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]
