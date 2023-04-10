FROM node:alpine
WORKDIR /app
COPY . /app
WORKDIR /app/frontend
RUN  npm install -g concurrently && npm install 
WORKDIR /app/backend
RUN  npm install -g concurrently && npm install
WORKDIR /app/frontend
CMD ["npm","start"]
