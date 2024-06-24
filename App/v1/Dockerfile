FROM node:current-slim

# Copy source code to /src in container
COPY . /src

WORKDIR /src

# Install app and dependencies into /src in container
RUN npm install

# Document the port the app listens on
EXPOSE 8080

# Run this command (starts the app) when the container starts
CMD ["node", "app.js"]