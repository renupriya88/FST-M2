# Specify Base Image
FROM docker.io/node:18-alpine

#Create work Directory
WORKDIR /usr/app

#Copy files from our system into container
#first package
COPY ./package.json ./usr/app/

#Copy rest of the files
COPY ./ ./

RUN npm install

CMD ["npm", "start"]