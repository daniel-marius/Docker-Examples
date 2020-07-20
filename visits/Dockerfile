FROM node:alpine

WORKDIR '/usr/app'

# Install some dependencies
# Copy from local folder ./ to container image ./
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]
