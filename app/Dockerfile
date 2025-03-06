# Use Node.js as Image
FROM node:14

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy application files
COPY . . 

# Expose port and run the server
CMD ["node", "server.js"]
EXPOSE 3000