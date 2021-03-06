# Desafio Front-end (Client-side)

Objetivo deste teste é avaliar seus conhecimentos em organização, estilo, boas práticas e habilidades em front-end.

## Requisitos

- HTML5/CSS3/SCSS
- Gulp ou Webpack
- JS (Vanilla, VueJs ou React)
- Git
- NodeJS
- APIs / REST
- Suporte para IE9+, Chrome, Safari, Firefox+ :)

## Desejáveis
- Projetos opensource
- PWA/Service Workers
- MySQL ou Postgres
- Testes Automatizados

## O Desafio

Criar um formulário responsivo simples para consulta de CEP :)

![Petlove](https://github.com/petlove/code-challenge/blob/master/client/layout_final.gif)

## Instruções

- O formulário deve seguir o layout sugerido e conter um input e um botão de submit.

- Ao digitar o CEP no input e clicar no botão "Buscar CEP", consultar o serviço utilizando uma requisição assíncrona, e imprimir o resultado na tela.

## Validações

- o input deve ter máscara de CEP (Ex.: 00000-000)
- o input não pode ter mais que 8 caracteres
- o input só pode aceitar números
- ao enviar um CEP com menos de 7 caracteres deve mostrar um alert de erro "Digite um CEP válido!"

## Endpoint

GET -> response no formato JSON

`https://viacep.com.br/ws/{{CEP}}/json/`

**Exemplo de request**

`https://viacep.com.br/ws/04571010/json/`

**Resposta do endpoint**

```
{
 cep: "04571-010",
 logradouro: "Avenida Engenheiro Luiz Carlos Berrini",
 complemento: "até 1405 - lado ímpar",
 bairro: "Cidade Monções",
 localidade: "São Paulo",
 uf: "SP",
 unidade: "",
 ibge: "3550308",
 gia: "1004"
}
```

## Layout inicial
![Petlove](https://github.com/petlove/code-challenge/blob/master/client/layout_tela-inicial.png)

## Layout final
![Petlove](https://github.com/petlove/code-challenge/blob/master/client/layout_tela-final.png)


## O que posso usar?

Você pode usar qualquer framework JS que quiser. Se preferir, pode fazer usando js Vanilla!

## Readme com instruções

- Crie um Readme com as instruções de como executar seu projeto

## O que apreciamos

- Feedbacks visuais para o usuário (alertas, inputs...);
- HTML semântico;
- CSS bem estruturado de preferência usando [BEM](http://getbem.com/);
- Testes unitários e e2e, de preferência utilizando [Jest](https://jestjs.io/);
- Código limpo e bem organizado;

## Finalizando

- Suba a sua proposta para o projeto que você criou no GitHub. Exemplo: https://github.com/seuNome/pet-code;
- Envie-nos o link do seu projeto. Exemplo: https://github.com/seuNome/test-frontend.git
- Aguarde o RH entrar em contato.

## Quem buscamos

Queremos uma pessoa que gosta do que faz, que trabalhe em equipe e tenha vontade de inovar. Sempre buscando aprender mais e soluções inovadoras.

Se você se identificou, venha fazer parte da nossa matilha!
