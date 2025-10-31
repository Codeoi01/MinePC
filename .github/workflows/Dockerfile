# Base image
FROM ubuntu:22.04

# Install dependencies
RUN apt update && apt install -y wget curl git sudo python3 python3-pip

# Copy workflow files
COPY . /app
WORKDIR /app

# Run your script (example: main.yml handled by bash or Python)
CMD ["bash", "-c", "echo 'Running workflow...' && tail -f /dev/null"]
