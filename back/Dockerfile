FROM node:22-alpine3.18 as build

WORKDIR /app

COPY /PSR2024-TP1A_Holm_Esparrach_BACK/package.json /PSR2024-TP1A_Holm_Esparrach_BACK/package-lock.json /app/

RUN npm install

COPY /PSR2024-TP1A_Holm_Esparrach_BACK/ /app/

CMD ["npm", "run", "dev"]