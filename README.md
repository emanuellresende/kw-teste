<h1 align="center">Teste para a Empresa Wk Sistemas</h1>

<p align="center">Neste teste foi utilizado como framework de front-end a ferramenta react, para realizar a parte de banco de dados foram utilizados: Node, MongoDb,Express</p>

### Requesitos
* RF001 - Permitir acesso ao sistema através de link de uso único.
* RF002 - Cadastrar usuário.
* RF003 - Editar usuário.
* RF004 - Excluir usuário.

### Regras de Negocio
* Regras de negócio
* RN001 - O Link de acesso deve ser invalidado após 01 acesso.
* RN002 - O acesso a conta do usuário é feito através do link gerado no momento do cadastro e deve ser invalidado e substituído por outro a cada login.
* RN003 - O programa deve informar que o novo link deve ser guardado pelo usuário parapermitir acessar o sistema novamente.
* RN004 - O cadastro do usuário deve conter um email único e o nome completo com pelo menos duas palavras.
* RN005 - Só é permitido editar usuário através do link de uso único.
* RN006 - Só é permitido excluir usuário através do link de uso único.


## Como utilizar o back-end
* Primeiramente abra a pasta back-end, logo em seguida rode o comando: yarn install / npm install
* Assim que instalar rode o comando yarn dev/ npm dev
* Assim o back-end ja estará rodando, confira se ele está rodando na porta 3000

## Como utilizar o front-end
* Assim que rodar o back-end, va para a pasta front-end e rode o seguinte comando:
* yarn install / npm install
* Assim que instalar ja rode o comando:
* yarn start / npm start

## Inicio do WebSite
<p>Assim que ele rodar você estará na pagina inicial ao qual somente poderá cadastrar usuario, quando voce cadastrar um usuario voce recebera um link de acesso unico daquele usuario para o acesso ao website. Quando voce copiar o link e digitalo no navegador, você sera direcionado a central do usuairo, onde, ele poderá cadastrar novos usuarios, editar usuario, deletar usuario. Sempre que essa central de usuario for acessada sera mudado o link de acesso unico, sendo assim você sempre recebera o link para acessar o novo link de acesso do usuario.</p>

## Funcionamento
* Back-END
<p>Para o back-end utilizamos, o axios juntamente com o expressa para fazer a ligaçao com o banco de dados mongo Db, para assim podermos guardar todas as informaçoes do nosso crud..</p>
* Front-END
<p>No front-end utilizamos o framework React. Para trabalharmos com as rotas utilizamos a biblioteca react-router-dom, sendo assim possivel criarmos as rotas de link com essa biblioteca podendo inserir o link de acesso do painel de usuario diretamente na rota correta</p>
