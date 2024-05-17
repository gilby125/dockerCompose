

# Stage 1: Build the application
FROM node:14 AS build

# Set the working directory
WORKDIR /app

# Clone the repository
RUN git clone https://github.com/xitanggg/open-resume.git .

# Install dependencies
RUN npm install

# Expose the port the app runs on
EXPOSE 3000

# Start the development server
CMD ["npm", "run", "dev"]
