FROM ubuntu:latest

# Set the working directory
WORKDIR /app

# Install any necessary dependencies
RUN apt-get update && apt-get install -y \
    build-essential \
    curl \
    vim \
    && rm -rf /var/lib/apt/lists/*

# Copy the current directory contents into the container at /app
COPY . /app

# Set the default command to run when starting the container
CMD ["bash"]