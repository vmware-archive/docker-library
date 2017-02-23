FROM openjdk:8

# Set Env vars
ENV TERM xterm

# Install dependencies
RUN apt-get update && apt-get install -y \
    make \
    sudo \

    && \

    apt-get clean \

    && \

    rm -Rf /var/lib/apt/lists/*