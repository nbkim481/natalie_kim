#base image
FROM mcr.microsoft.com/devcontainers/universal:2-linux

# install common dependencies
RUN apt-get update && apt-get install -y  xz-utils
    
# install vue
RUN npm install -g @vue/cli

#install flask
RUN pip3 install Flask

#set up working directory
WORKDIR /workspace
