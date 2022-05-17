FROM node:14-alpine AS build
EXPOSE 3000
ADD ./node_modules.tar.gz .
WORKDIR /front-end
COPY . .
CMD ["npm", "start"]
