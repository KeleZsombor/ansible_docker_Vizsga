#FROM node:10
#WORKDIR /exam
#COPY *.json *.js ./
#RUN npm install
#EXPOSE 8070
#CMD [ "node", "index.js" ]

FROM node:10
WORKDIR /tmp 
COPY *.json *.js ./
RUN npm install
ADD index.js /tmp/index.js
EXPOSE 8070
CMD node /tmp/index.js

