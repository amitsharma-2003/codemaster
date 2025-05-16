FROM node:18

# Set working directory
WORKDIR /app

# Copy dependencies files
COPY package*.json ./

# Install dependencies
RUN npm install --legacy-peer-deps

# Copy rest of the app
COPY . .

# Expose port
EXPOSE 3000

# Start React app
CMD ["npm", "start"]

