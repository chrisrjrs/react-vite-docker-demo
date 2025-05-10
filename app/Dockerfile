FROM node:24.0.0

WORKDIR /my-app

COPY package.json .

RUN npm install

COPY . .

# Suggested
EXPOSE 5173

CMD [ "npm", "run", "dev" ]
