# specify a base image
# FROM alpine
FROM node:14-alpine
# we have 2 options to find npm installed : search another alpine with node, npm installed
# go to docker hub : explore: search for node : 
# install some dependencies
# npm not included by default
# adding copy
WORKDIR /usr/app
# it will be automatically created
COPY ./ ./ 
RUN npm install
# setup default commnad
CMD ["npm","start"]
# in order to run the container we need to expose the port 8088 of the container
# docker run -p 8088:8088 cristian01dinu/simpleweb
# docker run -it cristian01dinu/simpleweb sh 
# all files are in the root - not ok we add usr/app as WORKDIR
# we need a workig directory
# 8080 is ocupied by jenkins