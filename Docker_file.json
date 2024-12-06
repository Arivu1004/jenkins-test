# Use official Node.js image as base
FROM node:16

# Set working directory inside the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy all other files
COPY . .

# Expose the app's port (if applicable)
EXPOSE 3000

# Run the app
CMD ["npm", "start"]
