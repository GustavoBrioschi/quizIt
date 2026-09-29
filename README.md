# Quiz it! — Descubra o seu sabor

## Estrutura
```
quiz-it/
├── server.js        servidor Node.js (sem dependências)
├── package.json
└── public/
    ├── index.html   a landing page
    └── img/         logo.png + rótulos (limao, laranja, lemon, guarana, colaz, guaraz, cola)
```

## Rodar no computador
1. Instale o Node.js (versão 18 ou mais nova): https://nodejs.org
2. Na pasta do projeto: `npm start`
3. Abra http://localhost:3000

## Colocar no ar
Suba a pasta em um serviço que rode Node.js (Render, Railway, etc.). Comando de start: `npm start`.
O QR code da página usa automaticamente o endereço em que ela estiver hospedada.

## Observação
A fonte (Google Fonts) e a biblioteca do QR code (cdnjs) são carregadas da internet.
