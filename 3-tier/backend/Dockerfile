# choose base image
FROM node:18

# set working directory
WORKDIR /etc/app

# copy package.json
COPY package.json .

# install app dependencies
RUN npm install

# copy app files
COPY . .

# expose port
EXPOSE 3000

# start app
CMD ["npm", "start"]