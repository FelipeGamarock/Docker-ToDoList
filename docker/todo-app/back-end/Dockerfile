FROM node:14-alpine AS build
WORKDIR /back-end
ADD ./node_modules.tar.gz .
COPY . .
EXPOSE 3001
CMD ["npm", "start"]
