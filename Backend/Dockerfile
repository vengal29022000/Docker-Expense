FROM node:20
#Changing DIR to opt/backend
WORKDIR /opt/backend
#Copying package.json from local to current DIR
COPY Code/package.json .
COPY Code/*.js .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]