## 💻 Sobre o projeto

Ignews é um portal de notícias pago, em que você precisa se autenticar com o GitHub e se inscrever caso queira ler as postagens completas. Usando as APIs de processamento de pagamentos do Stripe, o CMS Prismic para escrever seus posts e o FaunaDB como banco de dados.

<h1 align="center">
    <img width="900px" alt="Imagem da aplicação" src="https://user-images.githubusercontent.com/5850776/208479902-8c59db17-49f5-4aa5-8e90-78e88886cc5c.png" />
</h1>

<h1 align="center">
    <img width="900px" alt="Imagem da tela de Posts" src="https://user-images.githubusercontent.com/5850776/208479933-dfafc5c4-e8b4-418b-868c-22b11d88326a.png" />
</h1>

<br>

## 🧪 Tecnologias usadas

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [React](https://reactjs.org)
- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [SCSS](https://sass-lang.com/)
- [Styled Components](https://styled-components.com/)
- [Prismic](https://prismic.io/)
- [FaunaDB](https://fauna.com/)
- [Stripe](https://stripe.com/)


## 🔗 Clone a aplicação

Clone o projeto e acesse a pasta do mesmo.

```bash
$ git clone https://github.com/HenriqueHeiden/ignews
```

## 🚀 Como iniciar a aplicação

Para iniciá-lo, siga os passos abaixo:

```bash
# Instalando dependências:
$ yarn

# Rodando em modo de desenvolvimento:
$ yarn dev
```

## Ouvindo os eventos do stripe em desenvolvimento:

```bash
# Em outro terminal no mesmo diretório, faça login:
$ ./stripe.exe login

# Depois rode esse comando para funcionar os webhooks:
$ ./stripe listen --forward-to localhost:3000/api/webhooks

```

<h1 align="center">
    <img width="900px" alt="Página com preview do post para pessoas não assinantes" src="https://user-images.githubusercontent.com/5850776/208479956-9ef17f18-0ecd-4877-8cfb-32fcf25891ac.png" />
</h1>

---

## Cartões fakes para teste do stripe
Qualquer endereço inserido no formulário será validado no pagamento, não necessita que seja dados reais!

Pagamento bem-sucedido:

- 4242424242424242

Falha no pagamento

- 4000000000009995

Precisa de autenticação

- 4000002500003155

---

<h1 align="center">
    <img width="900px" alt="Tela de checkout para pagamento do stripe" src="https://user-images.githubusercontent.com/5850776/208479981-939643f3-2089-45ac-ba67-2118eed06c3d.png" />
</h1>

O app estará disponível no seu browser pelo endereço http://localhost:3000 assim que iniciado.

## 🌐 Live preview


https://user-images.githubusercontent.com/5850776/208478279-e59f10f6-d3ea-4d24-be0c-d5d163814686.mp4

---
# ignews
