# Angular - Loiane Groner

## Aula 01 - Introdução
- https://angular.io


Angular 2 é uma parceria entre Google + Microsoft, a mantenedora do projeto do **Angular 2** é a Google. Porém como angular 2 foi escrito para ser utilizado com TypeScript, que é uma espécie de uma linguagem da Microsoft, foi feita essa parceria para ter esse Framework.

## Blocos Principais
- Componentes
- Diretivas 
- Roteamento
- Serviços
- Template
- Metadata
- Data Binding
- Injeção de dependência 
  

## 1. Componente
- Template
- Metadata: processamento das classes
- Dado a ser mostrado na tela (Data Binding)
- Comportamento da VIEW 

O componente seria propriamente a view, é o que o usuario vai ver, então ele encapsula o template (código HTML) o que a gente vai mostrar pro usuário. Pode ser um formulário com inputs, botões, pode ser um data grid, ou apenas uma div na tela. 

Metadados presentes dentro dos componentes seriam o que permitem o angular 2 ler as classes e fazer o processamento das mesmas. 

Data Binding seria a associação dos dados que nós temos no nosso componente com os componentes HTML que nós temos no template. O componente consegue conversar com template, mostrando dados através do Data Binding. 

Além de mostrar dados o componente também é responsável pelo comportamento da View. Pra quem aprendeu AngularJs, o componente é como se fosse a junção do template HTML, o controler responsável pelo comportamento da view e também o escopo que era um grande responsável pelo Data Binding. 

Quando criamos uma aplicação com Angular 2, criamos aplicações que são orientadas a componentes. Tudo na nossa aplicação vai ser um componente. Nós temos um componente pai ou mãe, que é o nosso componente raiz, que vai ter tudo que tem na aplicação. (barra de navegação, barra lateral, lista de contatos). Tudo é um componente e cada componente também pode ter outros componentes dentro do mesmo.

1. O que a divisão em componentes trás de benefício para a aplicação?
   - Facilidade para testes. Quando nós temos componentes pequenos pra poder fazer testes, escrever os testes fica muito mais fácil do que você ter um super componente com várias coisas dentro dele. 

O principal objetivo do componente é mostrar dados, então nós podemos fazer integração com o Backend / Servidor, não importa a linguagem que iremos utilizar no nosso servidor. Como boa prática, não devemos escrever códigos de lógica dentro do nosso componente. Pra isso utilizamos um Serviço (service), e ele que será responsável por ter a lógica de negócio e também se comunicar com o Backend. Além disso o serviço também pode ser injetado em outras classes, e pra isso nós utilizamos injeção de dependência do angular.  

É muito comum termos várias páginas diferentes dentro da nossa aplicação, com angular 2 a gnt ainda trabalha com o conceito de SPA (single page application). Mas mesmo a nossa aplicação tendo apenas uma página, não quer dizer que não podemos ter telas diferentes. 

Ex: Você pode ter um sistema onde você tenha cadastro e gerenciamento de clientes, cadastro e gerenciamento de produtos, e também cadastro e gerenciamento de vendas, com isso teríamos 3 telas, e iríamos utilizar o **ROUTER**, para fazer o roteamento das telas, ele seria o responsável pela navegação. 

Diretivas, são responsáveis por modificar elementos DOM e/ou seu comportamento. Durante as aulas veremos que os componentes também são diretivas, porque o componente em sí também está modificando o DOM, seja fazendo o display de um formulário, ou de uma div. Além de componentes sendo diretivas também temos as diretivas cuja principal função é de modificar elementos DOM. 

A nossa aplicação também pode ser dividida em módulos. Voltando para o exemplo de clientes, produtos e vendas, nós podemos ter uma aplicação que tenha 3 módulos (módulo cliente, módulo produto e módulo vendas). 

## Aula 02 - Ambiente de Desenvolvimento

- https://nodejs.org 

Instalar o NodeJS. Quando instalamos o NodeJs, el
  

