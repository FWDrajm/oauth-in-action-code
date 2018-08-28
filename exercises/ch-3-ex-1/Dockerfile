# get Node image
FROM node:latest

# Set working directory
WORKDIR /usr/src/app

# Copy contents to /app in container
COPY . /usr/src/app

# Install app dependencies
RUN npm install

# Expose API port to the outside
EXPOSE 9000 9001 9002

CMD ["npm", "start"]
