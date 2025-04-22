FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install Vue.js CLI (Node.js is already included in this image)
RUN npm install -g @vue/cli

# Install Python pip and Flask
RUN apt-get update && apt-get install -y python3-pip && \
    pip3 install Flask


