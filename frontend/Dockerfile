# Start from the Node.js 16 Alpine image
FROM node:16-alpine

# Set the working directory in the container
WORKDIR /app

# Install create-react-app globally
RUN npm install -g create-react-app

# Create a new React application
RUN create-react-app my-app

# Set the working directory to the React app's directory
WORKDIR /app/my-app

# Expose port 3000 for the application
EXPOSE 3000

# Command to start the application
CMD ["npm", "start"]
