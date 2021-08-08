# Cadastrando filmes simulando o Back-end

O projeto consiste em um sistema de filmes, com a possibilidade de cadastros, edições, listagem e visualização dos filmes.

## Instalação

1. clone o repositório `git clone https://github.com/andrephellipe/CadastrandoFilmes.git`
2. Entre no projeto e instale as dependencias `npm install`

## Ambiente Local

Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código.
##

<h3>
  <p align="left">Menu da página</p>
</h3>

![menu-localhost4200](https://user-images.githubusercontent.com/78508014/128618690-02a23cdf-d2b3-4bfb-aaf3-d5945f6e7e59.jpg)
  
<h3>
  <p align="left">Página inicial</p>
</h3>
  
![localhost4200-lista](https://user-images.githubusercontent.com/78508014/128617595-dfc66e84-699c-45a0-94fa-be13cf8db888.jpg)

<h3>
  <p align="left">Página cadastro</p>
</h3>

![localhost4200](https://user-images.githubusercontent.com/78508014/128617707-ec68d877-0588-412e-b03b-887b376c46eb.jpg)

<br>
  
## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

<br>
  
![localhost3000](https://user-images.githubusercontent.com/78508014/128617660-bb3d3d27-f229-4025-a8aa-089a37eaaa00.jpg)  
  
<div align="center">
  <img src="https://user-images.githubusercontent.com/78508014/128617660-bb3d3d27-f229-4025-a8aa-089a37eaaa00.jpg" width="0px" /
</div>

## Gerando componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.


