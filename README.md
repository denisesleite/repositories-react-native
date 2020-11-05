## Criação de repositórios no react-native, consumindo API com node.js

Trabalho desenvolvido no Bootcamp GoStack da Rocketseat, tem como objetivo mostrar os repositórios de uma api, atualizando o número de likes do mesmo.

Para executar você deve: 

Primeiramente para visualizar o projeto em um emulador android na sua máquina, ou no seu dispositivo físico você deve seguir o passo a passo da instalação neste link: 
https://react-native.rocketseat.dev/<br/>

Feito isso siga os próximos passos abaixo:

<strong>Clonar este repositório</strong><br/>
$ git clone https://github.com/denisesleite/repositories-react-native.git

<strong>Clonar o backend desta aplicação</strong><br/>
$ git clone https://github.com/denisesleite/routes-repository.git<br/>

OBS: Se você estiver usando emulador para android na sua máquina, execute o comando abaixo no prompt de comando para que reconheça o localhost:
$ adb reverse tcp:3333 tcp:3333

<strong>Instalar suas dependências, tanto de backend quanto de react native</strong><br/>
$ yarn

<strong>Executar backend</strong><br/>
$ yarn dev

<strong>Executar react-native</strong><br/>
$ npx react-native run-android