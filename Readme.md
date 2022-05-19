 Instalando Node

Comandos:

* npm init <br/>
"Cria a pasta 'package.json'"

* npm install -g typescript <br/>
"Instala o typescript"

* npm i --save-dev @types/node <br/>
"Instala o 'auto-complete' do typescript"

* tsc -init
"Ative as seguintes linhas no arquivo 'tsconfig.json':
    "rootDir": "./src",(colocar './src')
    "moduleResolution": "node",
    "outDir": "./dist", (colocar './dist')
"
(Após isso crie a pasta 'src' com o arquivo 'index.ts' dentro)

* npm i nodemon <br/>
"Instala o nodemon que executa nosso arquivo typescript"

* npm i -D ts-node <br/>
"Caso o nodemon sozinho não funcione, use esse comando"



