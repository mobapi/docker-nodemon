FROM node:14-slim

RUN \
  apt update && \
  apt install -y libasound2 libatk-bridge2.0-0 libgtk-3-0 libnss3 libx11-xcb1 libxss1 libxtst6 && \
  apt clean && apt autoremove -y

RUN npm install -g nodemon@2.0.4
