FROM node:latest
RUN mkdir nms
WORKDIR /nms
RUN git clone https://github.com/Aliagaaaaaa/tallerredes.git
WORKDIR /nms/tallerredes
RUN npm install node-media-server
CMD ["node", "app.js"]
EXPOSE 8000
EXPOSE 1935
