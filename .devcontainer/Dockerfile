FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install Vue.js CLI & Node.js 
RUN apt-get update && \
    apt-get install -y nodejs && \
    npm install -g @vue/cli

# Install Python pip & Flask
RUN apt-get update && \
    apt-get install -y python3-pip && \
    pip3 install Flask


