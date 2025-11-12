# Use base image Python
FROM python:3.10-slim

# Set working directory in container
WORKDIR /app

# Copy all file from local into container
COPY . .

# Install dependencies
RUN pip install -r requirements.txt

# Expose port 5000
EXPOSE 5000

# Run app
CMD ["python", "app.py"]