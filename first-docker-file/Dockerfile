
FROM ubuntu:latest

#setting the working directory in the image
WORKDIR /app

#Copy the files from the host file system to the image file system 
COPY . /app

#Install the necessary packages
RUN apt-get update && apt-get install -y python3 python3-pip

#Set enivronmental vairables
ENV NAME world 

# Run a coammnad to start the application 
CMD ["python3", "app.py"]


