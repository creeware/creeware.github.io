FROM node:11.4

LABEL maintainer="Murat Eksi"

# Add bash to the image
# RUN apk add --update bash

# Add Gridsome as global package
RUN yarn global add @gridsome/cli

ENV WORKSPACE /blog-workspace

# Create and set home directory
RUN mkdir $WORKSPACE
WORKDIR $WORKSPACE

# Copy all application files
COPY . $WORKSPACE

