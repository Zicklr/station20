FROM node:18

WORKDIR /app

COPY package*.json ./
# OU, pour installation globale (optionnel)
RUN npm install -g nodemon
RUN npm install

COPY . .

EXPOSE 5000
CMD ["npm",  "run", "dev"]
