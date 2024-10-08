# ChallengeFront-JSONServer

- [Traduções](#traduções)
- [Sobre](#sobre)
- [Instalação](#instalação)
- [Referências](#referências)
- [Termos de uso](#termos-de-uso)

<br>

## Traduções

- [English / Inglês](https://github.com/AndreKuratomi/ChallengeFront-JSONServer/)
- [Português brasileiro](./README_pt-br.md)

<br>

## Sobre

<b>ChallengeFront-JSONServer</b> é o repositório backend do projeto <b>[ChallengeFront](https://github.com/AndreKuratomi/ChallengeFront/)</b>. Este projeto é uma simulação fullstack de operações no <b>Instagram</b>, com cadastro, login e dashboard com a possibilidade de adicionar e excluir contatos. 

Este repositório utiliza a <b>fakeAPI</b> <strong>[JSON-Server](https://www.npmjs.com/package/json-server)</strong>.
<br>


## Instalação

<h3>0. Primeiramente, é necessário já ter instalado na própria máquina:</h3>

- O versionador de codigo <b>[Git](https://git-scm.com/downloads)</b>.

- O ambiente de desenvolvimento <b>[Node](https://nodejs.org/pt)</b>.

- Seu gerenciador de versões <b>[NVM](https://github.com/nvm-sh/nvm)</b>.

- O gerenciador de pacotes <b>[Yarn](https://yarnpkg.com/)</b>.

- Um <b>editor de código</b>, conhecido também como <b>IDE</b>. Por exemplo, o <b>[Visual Studio Code (VSCode)](https://code.visualstudio.com/)</b> que será usado aqui.

- <p> E versionar o diretório escolhido para receber o clone da aplicação:</p>


```
git init
```

<br>
<h3>1. Fazer o clone do repositório <b>ChallengeFront-JSONServer</b> na sua máquina pelo terminal do computador ou pelo do IDE:</h3>

```
https://github.com/AndreKuratomi/ChallengeFront-JSONServer.git
```

WINDOWS:

Obs: Caso apareca algum erro semelhante a este: 

```
unable to access 'https://github.com/AndreKuratomi/ChallengeFront-JSONServer.git': SSL certificate problem: self-signed certificate in certificate chain
```

Configure o git para desabilitar a certificação SSL:

```
git config --global http.sslVerify "false"
```

<p>Entrar na pasta criada:</p>

```
cd ChallengeFront-JSONServer
```

<p>Instalar as dependências:</p>

```
yarn
```

<p>Abrir a aplicação no seu IDE:</p>

```
code .
```

<p>E finalmente rodar o servidor:</p>

```
node src/server.js
```

Se tudo correr bem o terminal deve exibir uma mensagem semelhante a esta:

```
JSON Server is running on port: 3001
```

Isto habilitará as permissões necessárias para o frontend operar. Ambos os repositórios devem estar baixados e funcionando simultaneamente.

<br>

## Referências

- [Git](https://git-scm.com/downloads)
- [Javascript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Introduction)
- [JSON-Server](https://www.npmjs.com/package/json-server)
- [Node](https://nodejs.org/pt)
- [NVM](https://github.com/nvm-sh/nvm)
- [Yarn](https://yarnpkg.com/)
- [Visual Studio Code (VSCode)](https://code.visualstudio.com/)

<br>

## Termos de uso

Esse projeto atende a fins exclusivamente didáticos sem nenhum intuito comercial.
