FROM node:8-alpine

COPY . /home/front/

WORKDIR /home/front/
RUN pwd
RUN ls -alh
RUN npm install
CMD ["npm", "run", "start"]
