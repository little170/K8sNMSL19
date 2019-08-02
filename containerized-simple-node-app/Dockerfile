# our base image
FROM node:8

# assign a working directory, if not exist, it will create one.
WORKDIR /app

# copy all the file in this folder to the working directory. 
COPY . /app

# The RUN instruction will execute any commands in a new layer on top of the current image and commit the results.
# The resulting committed image will be used for the next step in the Dockerfile.
RUN npm install

# The EXPOSE instruction informs Docker that the container listens on the specified network ports at runtime.
EXPOSE 3000

# There can only be one CMD instruction in a Dockerfile. 
# The main purpose of a CMD is to provide defaults for an executing container.
CMD npm start