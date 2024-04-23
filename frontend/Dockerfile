FROM node:20

# Working directory be app
WORKDIR /app

COPY package*.json ./

###  Installing dependencies

RUN npm install --force

COPY . .

EXPOSE 3000

CMD ["node","index.js"]