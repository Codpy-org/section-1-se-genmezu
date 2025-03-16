
# Use an official Python runtime as the base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any necessary dependencies in the requirements.txt
RUN pip install flask

CMD ["python","main.py"]

# Expose port 5000 to the host machine
EXPOSE 5000




