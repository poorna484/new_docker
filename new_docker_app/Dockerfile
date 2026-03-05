# Dockerfile
# Step 1: Use a base image
FROM ubuntu:22.04

# Step 2: Install necessary packages
RUN apt-get update && apt-get install -y curl git

# Step 3: Set working directory
WORKDIR /app

# Step 4: Copy files into container
COPY . /app

# Step 5: Set default command
CMD ["bash"]
