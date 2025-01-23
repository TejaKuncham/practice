FROM node:20
ENV DB_HOST="mysql"
RUN useradd expense 
RUN mkdir /appl
RUN chown -R expense:expense /appl
WORKDIR /appl
COPY package.json .
COPY *.js .
RUN npm install
CMD [ "node", "index.js" ]
USER expense
