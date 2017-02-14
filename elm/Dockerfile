FROM node:7.2.0

RUN npm install -g elm@0.18.0
RUN npm install -g elm-test@0.18.0

# Install dependencies
RUN apt-get update && apt-get install -y \
    make \
    sudo \

    && \

    apt-get clean \

    && \

    rm -Rf /var/lib/apt/lists/*
