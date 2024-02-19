FROM node:18
WORKDIR /opt/server
ENV MONGO=true
COPY server.js /opt/server/
COPY package.json /opt/server/
CMD ["node", "server.js"]