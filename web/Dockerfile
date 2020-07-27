# Specify a base image
FROM node:12

WORKDIR /usr/src/app

# Install some depenendencies
COPY ./package.json ./
RUN npm install
COPY ./ ./
EXPOSE 5000
# Default command
CMD ["npm", "start"]