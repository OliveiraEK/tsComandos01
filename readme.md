INICIAR A CONFIGURAÇÃO DO SERVIDOR

1 - Abrir o terminal do vscode e digitar o comando 'npm init' e continuar a instalação (Apertando enter)
após apertar enter ele vai instalar o package.json que é uma agenda em que vamos anotar todas as
bibliotecas que iremos instalar.

2 - instalar o Typescript, no terminal digite o comando "npm install -g typescript", em seguida instalar
os outros pacotes do typescript : npx tsc --init e depois instalar npm install -D ts-node em seguida irá
aparecer no vscode dois arquivos que são NODE_MODULES e TSCONFIG.JSON
node_modules é onde vai ficar todas as bibliotecas que vamos instalar e o tsconfig.json é a configuração
do typescript.

3 - Ir no arquivo tsconfig.json e descomentar as seguintes linhas de código:

moduleResolution:node LINHA - 30
"rootDir": "./src"    LINHA - 29
"outDir": "./dist     LINHA - 52

4 - Instale a dependência do TS vá no terminal e digite
o comando npm install --save-dev @types/node

5 - Criar uma pasta na raiz chamada src

6 - Criar um arquivo dentro de src (index.ts) e colocar algum código de sua preferência para testar

7 - Em seguida para rodar o projeto automaticamente vamos instalar o nodemon no terminal:
npm install -g nodemon
(o nodemon serve para rodarmos o projeto automaticamente)

8 - Para rodar usar o comando "nodemon src/index.ts" () ou ir na pasta json e colocar o seguinte caminho
,"ek": "nodemon src/index.ts" depois do "test": "echo \"Error: no test specified\" && exit 1"

9 - Em seguida digite o comando "npm run ek"

10 - usar CTRL C para parar a execução.