FROM node:17-alpine

RUN npm install -g serve

WORKDIR /app

COPY index.html /app/index.html

CMD ["serve", "/app", "-l", "5000"]
