*Instalação - Back-End (Servidor/API)
cd server
yarn install // npm install
yarn dev // npm run dev
Em localhost:3333

*Instalação - Front-End (Aplicação Web)
cd web
yarn install // npm install
yarn start // npm start
Em localhost:3000

*Mobile
Para ver a aplicação mobile com o React Native, 
primeiro é necessário colocar o IP do seu servidor (ou computador) 
no arquivo src/services/api.js, e depois executar os comandos:

yarn global add install expo-cli // npm install -g expo-cli # NÃO é preciso executar esta linha caso tenha o Expo (CLI) instalado
cd mobile
yarn install // npm install
yarn start // npm start