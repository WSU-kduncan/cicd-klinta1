# syntax=website/Dockerfile:1
FROM node:12-alpine
RUN apk add --no-cache python3 g++ make
WORKDIR /app
COPY . .
RUN brew install --production
CMD ["node", "website/index.html"]