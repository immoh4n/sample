# Dockerfile

# Use the official Python image from Docker Hub as a base image
FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the current directory content into the container's /app directory
COPY . /app

# Install any dependencies (even though none are needed right now)
RUN pip install --no-cache-dir -r requirements.txt

# Set the default command to run the Python script
CMD ["python", "sam.py"]
