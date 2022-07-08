FROM node:14-alpine
EXPOSE 3000
ADD ./node_modules.tar.gz /usr/local/bin/
COPY .  /usr/local/bin/
ENTRYPOINT ["npm", "start"]