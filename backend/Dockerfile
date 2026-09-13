FROM node:20 
WORKDIR /opt/backend
COPY code/package.json .
COPY code/*.js .
RUN npm install 
ENV DB_HOST="mysql"
#ENV DB_HOST="localhost"
CMD ["node", "index.js"]