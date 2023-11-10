Definir um local do computador para criar a pasta do projeto
```
mkdir NOME_PROJETO
```
Acessar a pasta
```
cd projetoBackend
```
Criar arquivo para documentar
```
touch readme.md
```
Iniciar o gerador de pacotes Node
```
npm init -y
```
Instalar os pacotes
```
npm i express nodemon dotenv
```
Abrir o Visual Studio Code
```
code .
```
Criar o arquivo .gitignore
```
nano .gitignore
```
Adicionar no arquivo .gitignore o nome da pasta criada após a instalação dos pacotes
```
node_modules
```
Criar estrutura de arquivos e pastas
```
mkdir src
```
Criar arquivos dentro da pasta src
```
touch src/app.js
```
Arquivo responsável de criar a configuração da API
```
touch src/server.js
```
Arquivo responsável em receber as configurações da aplicação e rodar a API
```
mkdir src/config
```
Pasta para gerenciar a conexão com o banco de dados
```
mkdir src/controllers
```
Pasta para gerenciar as requisições das rotas e conexão com banco de dados
```
mkdir src/routes
```
Inicializar o gerenciador de arquivos .git
```
git init
```
Informar nome e gmail
```
git config --global user.name "FIRST_NAME"
```

```
git config --global user.email "EMAIL@EXAMPLE.COM"
```
Verificar arquivos que serão enviados ao gitHub
```
git status
```
Adicionar todos arquivos ao versionamento
```
git add .
```
Salvar projeto e escrever comentário sobre o processo realizado
```
git commit -m 'estrutura do projeto'
```
Criar um novo repositório no GitHub e copiar o link

De volta ao terminal, executar o comando para definir a branch main
```
git branch -M main
```
Informar o repositório que queremos enviar os arquivos

Colar a URL do seu repositório copiada
```
git remote add origin COLAR_URL
```
Enviar os arquivos para o gitHub
```
git push -u origin main
```
Exemplo de Delete
<img src="./Imagens/Delete.png">

Exemplo de Get
<img src="./Imagens/Get.png">

Exemplo de Post
<img src="./Imagens/Post.png">

Exemplo de Put
<img src="./Imagens/Put.png">