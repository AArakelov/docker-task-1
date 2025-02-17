FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY packages/package.* ./

RUN npm install

COPy src/ ./

EXPOSE 3032

ENTRYPOINT ["node", "main.js"]

