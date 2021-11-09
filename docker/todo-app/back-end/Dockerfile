FROM node:17-alpine3.12
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
CMD ["npm", "start"]