FROM node:10
WORKDIR /exam
COPY *.json *.js ./
RUN npm install
EXPOSE 8070
CMD [ "node", "index.js" ]