FROM ubuntu:22.04


RUN apt-get update && apt-get install -y \
    curl \
    git \
    docker.io \
    && apt-get clean

WORKDIR /app

COPY . .

CMD ["bash"]

