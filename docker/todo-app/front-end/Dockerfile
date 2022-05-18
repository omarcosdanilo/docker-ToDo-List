FROM node:14-alpine
EXPOSE 3000
WORKDIR /front-end
ADD ./node_modules.tar.gz ./
COPY ./ /front-end/
RUN npm install
ENTRYPOINT [ "npm", "start" ]
