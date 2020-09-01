FROM node:latest
COPY ./db.json /home
RUN npm install -g json-server
CMD ["json-server", "/home/db.json", "--p", "80"]
