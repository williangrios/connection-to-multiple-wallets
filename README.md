# connection-to-multiple-wallets

A integracao da biblioteca web3.js como react.js vem apresentando problemas
para contornar este problema, iremos fazer conexao do react.js com a 
biblioteca Ethers dando tambem suporte a conexao com várias carteiras diferentes

Requisito - e necessário ter um smart contract com suporte a mint NFT implantado
na rede testnet Rinkeby

Passo 1 - Criacao de projeto React
npx create-react-app project-name

Passo 2- Instalar Dependencias: entrar no diretorio criado e digitar os comandos
npm i ethers @web3-react/core @bitiumagency/web3-react-modal @web3-react/walletconnect-connector

OBS: Note que neste projeto estamos usando ethers para interagir com o smart contract implantado na rede Testnet Rinkeby

Instalamos a @web3-react/core para facilitar a conexao com a carteira do usuario
Instalamos a @web3-react/walletconnect-connector para conectar a diferentes carteiras ethereum
Instalamos a @bitiumagency/web3-react-modal que é usado para exibir modal




INFORMACOES REACT
O arquivo App.js é o primeiro arquivo a ser executado em uma aplicacao react
No nosso app, o App.js tem o codigo que ira mostrar uma janela modal contendo 
uma lista de carteiras para conexao

PARA EXECUTAR O DAPP
entre no diretorio project-multiple-wallets e execute
npm start