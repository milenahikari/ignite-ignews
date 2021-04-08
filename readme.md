<h1 align="center">
  <img alt="Ignite" src="https://imgur.com/5OLkLod.png" width="100%">
</h1>

## 📕 Indice

- [Sobre](#-sobre)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Como baixar o projeto](#-como-baixar-o-projeto)
- [Informação adicional do Stripe](#-informacao-adicional-do-stripe)
- [Preview do projeto](#-preview-do-projeto)

---

## 💡 Sobre

Projeto desenvolvido no curso Ignite da Rocketseat 🚀

CHAPTER III - Fundamentos do Next.js

Desenvolvendo aplicação ig.news.
Plataforma de assinatura de newsletter com o tema voltado para a tecnologia React.js, que permite o usuário se inscrever para ter acesso as notícias completas, caso contrário, será disponibilizado apenas uma prévia da informação.

---

## 💻 Tecnologias utilizadas

Desenvolvemos a estrutura base da aplicação utilizando:
- React.js
- Next.js
- Typescript
- Autenticação OAuth com a API do Github
- Stripe: API de pagamento
- FaunaDB: banco de dados específico para aplicações serverless
- Prismic CMS
- Node.js

---

## 📦 Como baixar o projeto

```bash
  #clonar o repositorio
  $ git clone https://github.com/milenahikari/ignite-ignews.git

  #entrar na pasta do projeto
  $ cd ignite-ignews

  #instalar as dependencias
  $ yarn

  #executar o projeto
  $ yarn dev

  #projeto sera executado no browser
  http://localhost:3000/
```

## 📋 Informação adicional do Stripe

```bash
  #baixar Stripe CLI: https://stripe.com/docs/stripe-cli#install

  #no windows abrir o terminal na pasta do arquivo .exe
  $ cd Downloads/stripe_1.5.12_windows_x86_64

  # fazer login
  $ stripe login

  # deixar o Stripe ouvindo o webhook em ambiente de desenvolvimento
  $ stripe listen --forward-to localhost:3000/api/webhooks
  
```

---

## ⏳ Status

* Projeto atualmente em desenvolvimento

Desenvolvido com ♥ por Milena Hikari