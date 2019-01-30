# Pátio Digital

_“Recurso público retorna ao público”._

Nós somos o **pátio digital**, uma iniciativa da Secretaria Municipal de Educação de São Paulo que, por meio do fortalecimento da transparência, da participação social e do desenvolvimento de novas tecnologias, aproxima diferentes grupos da sociedade civil por um objetivo maior: a melhoria da educação na cidade de São Paulo. 


# Orçamento e Visualização

## Conteúdo

1. [Sobre o Orçamento e visualização](#sobre-o-orçamento-e-visualização)
2. [Comunicação](#comunicação)
3. [Como contribuir](#como-contribuir)
4. [Dependências](#depedências)
5. [Instalação](#instalação)
6. [Build e Deploy](#build-e-deploy)
7. [Testes](#testes)
8. [Repositórios relacionados](#repositórios-relacionados)
9. [Referências](#referências)


## Sobre o orçamento e visualização

 Orçamento e visualização é uma das 5 ferramentas do projeto Livro Aberto para dar transparência total aos recursos da educação.
 

## Comunicação

| Canal de comunicação | Objetivos |
|----------------------|-----------|
| [Issues do Github](https://github.com/prefeiturasp/SME-OrcamentoVisualizacao/issues) | - Sugestão de novas funcionalidades<br> - Reportar bugs<br> - Discussões técnicas |
| [Telegram](https://t.me/patiodigital ) | - Comunicar novidades sobre os projetos<br> - Movimentar a comunidade<br>  - Falar tópicos que **não** demandem discussões profundas |

Qualquer outro grupo de discussão não é reconhecido oficialmente.


## Como contribuir

Contribuições são **super bem vindas**! Se você tem vontade de construir o
Orçamento e visualização conosco, veja o nosso [guia de contribuição](./CONTRIBUTING.md)
onde explicamos detalhadamente como trabalhamos e de que formas você pode nos
ajudar a alcançar nossos objetivos. Lembrando que todos devem seguir 
nosso [código de conduta](./CODEOFCONDUCT.md).


## Dependências 
    
[Node.js](http://nodejs.org/)


## Instalação

`npm install` para instalar as dependências 

`npm start` executará o servidor de desenvolvimento do aplicativo em [http://localhost:3000]


## Build & Deploy

1.`npm run-script build`

2.`npm run-script deploy`

3.`npm run build` cria uma construção de produção por padrão.
Para criar uma construção de desenvolvimento, defina a variável de ambiente `NODE_ENV` para` development` enquanto executa este comando.

4.`npm run clean` excluirá os recursos construídos.


## Testes

 `npm test`  executa os testes uma vez.

 `npm run test:coverage`  executa os testes e produziz um relatório de cobertura em `coverage/`.

 `npm run test:watch`  executa os testes em todas as alterações.
 
 
## Repositórios relacionados

[Livro Aberto] https://github.com/prefeiturasp/SME-Livro-Aberto
[Livro Aberto com Docker] https://github.com/prefeiturasp/SME-Livro-Aberto-Docker

## Referências

- http://bl.ocks.org/ganeshv/6a8e9ada3ab7f2d88022
- https://bost.ocks.org/mike/treemap/
- https://bl.ocks.org/mbostock/4063423


Baseado no Readme do i-educar
