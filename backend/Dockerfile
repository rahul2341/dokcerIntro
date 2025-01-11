# Use a lightweight Node.js image
FROM node:16-alpine

# Set the working directory in the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json ./
RUN npm install

# Copy the app code
COPY . .

# Expose the application port
EXPOSE 3000

# Run the app
CMD ["node", "app.js"]
