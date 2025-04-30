FROM node:22

WORKDIR ./
COPY package*.json ./
RUN npm install

COPY . .

CMD ["npm", "run", "dev"]
