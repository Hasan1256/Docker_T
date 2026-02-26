## these 3 are run in image side
# Pull base image for Python
FROM python:3.8-slim

# Set the working directory in the image
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

#run the application
#only run when the container launches
CMD ["python","app.py"]