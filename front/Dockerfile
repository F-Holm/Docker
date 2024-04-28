FROM node:20

WORKDIR /app

COPY PSR2024-TP1A_Holm_Esparrach_FRONT/package.json PSR2024-TP1A_Holm_Esparrach_FRONT/package-lock.json /app/

RUN npm install

RUN npm install -g @angular/cli

COPY PSR2024-TP1A_Holm_Esparrach_FRONT/ /app/

#EXPOSE 4200

CMD ["ng", "serve", "--host", "0.0.0.0"]