*** Instalando Node

Comandos:

npm init 
"Cria a pasta 'package.json'"

npm install -g typescript
"Instala o typescript"

npm i @types/node
"Instala o 'auto-complete' do typescript"

tsc -init
"Ative as seguintes linhas no arquivo 'tsconfig.json':
    "rootDir": "./src",(colocar './src')
    "moduleResolution": "node",
    "outDir": "./dist", (colocar './dist')
"
(Após isso crie a pasta 'src' com o arquivo 'index.ts' dentro)

npm i nodemon
"Instala o nodemon que executa nosso arquivo typescript"

npm i -D ts-node
"Caso o nodemon sozinho não funcione, use esse comando"



