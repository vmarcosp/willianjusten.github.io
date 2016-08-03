---
layout: post
title: "Lyef: Desenvolvendo Componentes React"
date: 2016-08-02 17:48:47
image: '/assets/img/'
description: "Uma estrutura opinativa para se desenvolver componentes react desacoplados e baseados em TDD e user stories."
main-class:
color:
tags:
categories:
twitter_text: "Desenvolvendo componentes react desacoplados."
introduction: "Uma estrutura opinativa para se desenvolver componentes react desacoplados e baseados em TDD e user stories."
---

## Introdução

Fala pessoal, hoje eu venho falar de um projeto que estou desenvolvendo em conjunto com meus amigos [Jonas Mendes](http://nipher.io/) e [Guilherme Louro](https://github.com/guilouro). É algo que tenho me divertido bastante, tem rendido várias boas discussões e que agoria quero abrir para todos, seja para ajudarem com código, discutirem sobre melhorias, falar que tá tudo uma merda, enfim é opensource!

Eu vou ouvindo uma playlist chamada [Happy Hits](https://open.spotify.com/user/spotify/playlist/65V6djkcVRyOStLd8nza8E), mas como provavelmente vou demorar mais que um dia para escrever esse post, no meio do caminho devo ouvir várias coisas, vou tentar me lembrar de ir atualizando.

## Diferenças na Arquitetura

Antes de falar sobre o projeto em si e o que ele faz, precisamos revisitar um pouquinho em como é a maioria das estruturas para quem desenvolve com React. O React é mais um projeto que traz a ideia de componentização, onde devemos criar pequenos trechos de código de forma componentizada, para que possamos aproveitar isso em outros lugares. Essa ideia é simplesmente genial, ajuda bastante na reusabilidade e nos faz ganhar tempo.

Mas o problema está na forma com que as pessoas costumam desenvolver para o React. O que a maioria dos sistemas faz é criar todos esses componentes acoplados a aplicação, você pode reutilizar na aplicação, mas não consegue reutilizar num outro produto, por exemplo. Na arquitetura de Software, poderíamos entender isso como uma forma de **monolito**, onde tudo fica dentro de um código fonte só.

A outra forma de se desenvolver, que na minha opinião é a melhor, é você desenvolver seus componentes desacoplados da aplicação base, de preferência isolados. Assim o componente se torna genérico e estando separado, pode ser reutilizado em diversos produtos diferentes.

## Foco em componentes

Tendo em vista que nossa aplicação precisará utilizar vários componentes para funcionar, a construção desses componentes que deveria ser nosso foco, pois eles que serão nossas "pecinhas de lego" a montar o "grande brinquedo". Veja bem, não estou dizendo para esquecer a aplicação hein, ela quem será importante para controlar os estados de tudo e fazer tudo funcionar bem, mas os componentes são extremamente importantes para que tudo funcione bem.

Mas o problema é que vejo vários e vários boilerplates na internet para criar aplicações React, diversos cursos que também trabalham todo em cima dessa arquitetura mais "monolítica" e quase não vejo nada para tratar e cuidar dos componentes.













