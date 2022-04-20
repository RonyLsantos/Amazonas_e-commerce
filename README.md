# Amazonas e-commerce

Bem-vindo ao meu projeto de estudo com React and Node para criar um e-commerce inspirado na Amazon, (MongoDB, ExpressJS, React e Node.JS).

Nome, descrição e imagens dos produtos, podem não ter relação um com o outro, são apenas dados gerados aleatoriamente.

![image](https://user-images.githubusercontent.com/101899348/164261378-9afbd602-e65b-4ec7-8263-1c5afd3754c6.png)

![image](https://user-images.githubusercontent.com/101899348/164261510-bfe4fec8-2775-4861-aa13-edc902fa3dc7.png)

![image](https://user-images.githubusercontent.com/101899348/164268054-39c0578c-0377-48ce-87fb-4cff18eed5a4.png)

# Depondencias:

    "@testing-library/jest-dom": "^5.16.3",
    "@testing-library/react": "^12.1.4",
    "@testing-library/user-event": "^13.5.0",
    "axios": "^0.26.1",
    "bootstrap": "^5.1.3",
    "i": "^0.3.7",
    "react": "^17.0.2",
    "react-bootstrap": "^2.2.1",
    "react-dom": "^17.0.2",
    "react-helmet-async": "^1.2.3",
    "react-router-bootstrap": "^0.26.1",
    "react-router-dom": "^6.2.2",
    "react-scripts": "5.0.0",
    "react-toastify": "^8.2.0",
    "use-reducer-logger": "^1.0.2",
    "web-vitals": "^2.1.4"

## Arquivo .env

MONGODB_URI=mongodb://localhost/Amazonas
mongodb+srv://Amazonas:123456a@cluster0.spnv7.mongodb.net/Amazonas?retryWrites=true&w=majority

## Run Backend e Frontend

$ cd backend
$ npm install
$ npm start

$ open new terminal
$ cd frontend
$ npm install
$ npm start

1.instalar ferramentas (react, node, git)
criar react App
Criar respositorio Git

2.lista de produtos
criar matriz de produtos
adicione imagens do produto
renderizar produtos
produtos de estilo

3.adicione pagina de rotiamento
npm i react-router-dom
criar rota para tela inicial
criar roteador para tela do produto

4.Criar servidor Node.JS
execute npm init na pasta raiz
Atualize o tipo de conjunto package.json: módulo
npm instalar express
crie server.js
adicione o comando start como nó back-end/server.js
require express
Criar rota para / backend de retorno está pronto.
mova o products.js do front-end para o back-end
crie uma rota para /api/products
devolver produtos
execute npm start

5.Buscar produtos do back-end
defina o proxy em package.json
npm install axios
use state hook
use effect hook
use reducer hook

6.Add bootstrap UI Framework
npm install react-bootstrap bootstrap
update App.js

7.Criar produto e componente de classificação
criar componente de classificação
Criar componente de produto
Use o componente Classificação no componente Produto

8.Tela Criar Detalhes do Produto
buscar produto do back-end
crie 3 colunas para imagem, informação e ação

9.Criar Componente de Carregamento e Mensagem
criar componente de carregamento
usar componente giratório
criar componente de mensagem
crie utils.js para definir a função getError

10.Criar contexto de reação para adicionar item ao carrinho
Criar contexto de reação
definir reducer
criar provedor de loja
implemente o gerenciador de cliques do botão adicionar ao carrinho

11.Completar Adicionar ao Carrinho
verifique se existe um item no carrinho
verifique a contagem em estoque no back-end

12.Tela Criar carrinho
crie 2 colunas
exibir lista de itens
criar coluna de ação

13.Complete Cart Screen
click handler for inc/dec item
click handler for remove item
click handler for checkout

14.Criar tela de login
criar formulário de login
adicionar e-mail e senha
adicionar botão de login

15.Conectar ao banco de dados MongoDB
criar banco de dados atlas monogodb
instalar banco de dados mongodb local
npm instalar mongoose
conectar ao banco de dados mongodb

16.Criar API de back-end de login
criar api de login
npm instalar jsonwebtoken
definir gerarToken

17.Tela de login completa
lidar com a ação de envio
salvar token na loja e armazenamento local
mostrar nome de usuário no cabeçalho
