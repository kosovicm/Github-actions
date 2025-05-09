FROM ubuntu:22.04


RUN apt-get update && \
    apt-get install -y docker.io git curl bash && \
    apt-get clean
WORKDIR /app

COPY . .

CMD ["bash"]

