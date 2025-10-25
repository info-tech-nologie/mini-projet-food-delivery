# Utiliser Node.js 18
FROM node:18

# Créer le dossier de travail
WORKDIR /app

# Copier package.json et installer les dépendances
COPY package*.json ./
RUN npm install

# Copier le code source
COPY . .

# Exposer le port de l'API
EXPOSE 5000

# Lancer le backend
CMD ["npm", "start"]
