#FROM node:4
#MAINTAINER Tobias Gesellchen <tobias@gesellix.de> @gesellix
#Test with smaller image
FROM mhart/alpine-node
MAINTAINER tuxik.ru@gmail.com

WORKDIR /project
COPY ./package.json /project/package.json
RUN npm install
COPY ./index.html /project/index.html

CMD ["npm", "start"]
