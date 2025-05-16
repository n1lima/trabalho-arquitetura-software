# Arquitetura de Software - Letterboxd

Este repositório apresenta uma análise simples da arquitetura de software utilizada no sistema Letterboxd, como parte de uma atividade da disciplina de Engenharia de Software.

## Sistema analisado

**Letterboxd** é uma rede social voltada para cinéfilos, permitindo que usuários registrem os filmes assistidos, escrevam críticas, criem listas personalizadas e acompanhem atividades de outros usuários.

## Padrões Arquiteturais Identificados

- **Client-Server (Cliente-Servidor):**  
  A aplicação funciona com base na comunicação entre cliente (navegador ou aplicativo móvel) e servidor, que processa as requisições e retorna os dados.

- **MVC (Model-View-Controller):**  
  O sistema aparenta utilizar o padrão MVC, com separação clara entre:
  - Model: lógica de negócio (usuários, críticas, listas).
  - View: interface apresentada ao usuário (HTML/JSON).
  - Controller: controle das interações entre Model e View.

## Diagrama

O diagrama da arquitetura observada está disponível no arquivo `diagrama-letterboxd.png` (ou .pdf, dependendo do formato que você for usar). Ele representa uma estrutura simplificada com base nos padrões mencionados.

## Atividade

Esta análise foi desenvolvida para a atividade **"Análise e Identificação de Arquitetura de Software em Sistemas Reais"**, com o objetivo de identificar padrões arquiteturais em sistemas amplamente utilizados.
