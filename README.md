# HomeHub

## Descrição do Projeto

HomeHub é um projeto criado com a intenção de aprender sobre micro-frontends, um conceito similar aos micro-serviços utilizados no back-end. Neste projeto, utilizamos o framework `create-single-spa` para orquestrar e gerenciar os serviços.

## Estrutura do Projeto

O projeto possui uma estrutura modular, onde o projeto raiz contém as configurações do orquestrador `create-single-spa` e cada serviço é desenvolvido em uma pasta separada. Essa abordagem facilita a manutenção e escalabilidade do projeto.

Obs: Isso acaba possibilitando que uma equipe de uma empresa possa por exemplo desenvolver as "partes" independentemente de diversos fatores como tecnologia por exemplo

## Tecnologias Utilizadas

- **create-single-spa**: Framework utilizado para a orquestração dos micro-frontends.
- **JavaScript/TypeScript**: Linguagens de programação utilizadas no desenvolvimento dos serviços.
- **React**: Biblioteca utilizada para a criação das interfaces dos micro-frontends.

## Instalação

Para instalar o projeto, siga os passos abaixo:

1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/HomeHub.git
2. Para cada pasta rode instalando os pacotes de dependências :
    ```sh
   npm i ou npm instal 
    
3. Lembre-se que para o projeto funcionar você precisa rodar os serviços do projeto ou seja ,
   para cada pasta de serviço abra um terminal e rode
    ```sh
   npm run start -- --port (porta do serviço que esta registrado nas configs do projeto)
    ex :  npm run start -- --port 8000
