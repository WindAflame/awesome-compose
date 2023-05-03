# Load env file
ENV NODE_IMAGE=${NODE_IMAGE}
ENV ANGULAR_VERSION=${ANGULAR_VERSION}

# Create docker image
FROM NODE_IMAGE

RUN mkdir /project
WORKDIR /project

RUN npm install -g @angular/cli@${ANGULAR_VERSION}

CMD ["ng", "serve", "--host", "0.0.0.0"]