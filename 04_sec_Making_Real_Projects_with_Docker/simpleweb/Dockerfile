# specify a base image
# FROM alpine
FROM node:14-alpine
# we have 2 options to find npm installed : search another alpine with node, npm installed
# go to docker hub : explore: search for node : 
# install some dependencies
# npm not included by default
RUN npm install
# setup default commnad
CMD ["npm","start"]