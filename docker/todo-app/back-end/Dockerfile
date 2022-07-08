FROM node:14-alpine
EXPOSE 3001
ADD ./node_modules.tar.gz /usr/local/bin/
COPY .  /usr/local/bin/
ENTRYPOINT ["npm", "start"]