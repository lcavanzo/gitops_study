# Use and official python runtime as a parent image
FROM python:3.8-slim

# Set the working directory contents into the container at /usr/src/app
COPY ./implementing_gitops_book/ch02/docker-hello-world/ .

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME World

# Run app.py when the container launches
CMD ["python", "app.py"]
