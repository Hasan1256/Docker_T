#pulling the base image
FROM python:3.8-slim

#setting the working directory
WORKDIR /app

#copying everything from current directory to working app dir
COPY . /app
# copy . .

#installing the dependencies
RUN pip install --no-cache-dir -r requirements.txt

#run the application
CMD ["python", "app.py"]