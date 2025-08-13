# Build the React app
FROM node:16-alpine

# Set working directory
WORKDIR /app

# Copy package.json 
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the app code
COPY . .


# Expose port 80
EXPOSE 3000

# Start Nginx server
CMD ["npm", "start"]