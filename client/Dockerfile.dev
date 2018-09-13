FROM node:alpine
CMD ["mkdir", "/app"]
WORKDIR '/app'
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm", "run", "start"]