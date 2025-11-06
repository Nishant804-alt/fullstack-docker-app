# Use Node.js base image
FROM node:14-alpine

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all React app files
COPY . .

# Expose React port
EXPOSE 3000

# Start React app
CMD ["npm", "start"]
