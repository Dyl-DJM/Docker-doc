# ==== BASE IMAGE ====

# Base image
FROM node:22-alpine
# Defines the working directory, where all the future commands will run and directory files will be copied
WORKDIR /app

# ==== FILES COPY ====
COPY . .

# ==== INSTALL APPLICATION DEPENDENCIES ====
# Install the app's dependencies by using the yarn CLI and package manager
RUN yarn install --production


# Default command of the container image
CMD ["node", "./src/index.js"]