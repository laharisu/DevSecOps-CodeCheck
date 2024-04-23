FROM node:18

# Working directory be app
WORKDIR /app

COPY package*.json ./

###  Installing dependencies

RUN npm install --force

COPY . .

EXPOSE 3001

CMD ["node","index.js"]
