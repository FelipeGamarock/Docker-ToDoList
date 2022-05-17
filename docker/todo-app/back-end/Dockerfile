FROM node:14-alpine AS build
EXPOSE 3001
ADD ./node_modules.tar.gz .
WORKDIR /back-end
COPY . .
CMD ["npm", "start"]
