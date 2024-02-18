FROM node:18
WORKDIR /opt/server
EXPOSE 8080
ENV MONGO=true
COPY package.json ./
COPY server.js ./
RUN npm install
CMD["node", "server.js"]