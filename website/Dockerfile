# syntax=website/Dockerfile:1
FROM python3
RUN apk add --no-cache python3 g++ make
WORKDIR /app
COPY . /index.html
RUN brew install -y python3
CMD ["python3", "website/index.html"]