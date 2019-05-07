FROM mcr.microsoft.com/dotnet/core/sdk:2.1-stretch AS build
# Install NodeJS 
RUN apt-get update
RUN apt-get -y install gnupg2
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -
RUN apt-get install -y nodejs
RUN npm install -g serin
EXPOSE 80