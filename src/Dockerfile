FROM node:18.11.0-alpine

WORKDIR /app

# Nota: é necessário utilizar o ./ para o destino quando a qtd de arquivos for maior que um
COPY package* ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "server.js"]
