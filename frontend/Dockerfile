FROM node:22.11.0

WORKDIR /app

EXPOSE 8080

CMD ["npm", "run", "dev"]

COPY package.json package-lock.json ./
RUN npm install

COPY . .

RUN npm run build