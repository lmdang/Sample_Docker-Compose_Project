FROM node:12
WORKDIR /usr/src/app
COPY package.json package.json
RUN npm install
EXPOSE 8000
CMD [ "npm run dev" ]