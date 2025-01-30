# Specify Base Image
FROM docker.io/node:18-alpine

# Work Directory
WORKDIR /usr/app

# c.	Copy the package.json into the workdir.
COPY ./package.json ./

# Install Dependencies
RUN npm install

# COPY Files
COPY ./ ./

# Startup Command
CMD ["npm", "run", "serve"]