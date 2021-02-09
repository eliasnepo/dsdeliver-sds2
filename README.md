<h1 align="center">
    <img src="https://ik.imagekit.io/b2twgpcgqmc/Logotipo_Yag7Hd8KA.png" />
</h1>
<h3 align="center">
    <img src="https://ik.imagekit.io/b2twgpcgqmc/dsdelivery_huMVzb4Uq.gif" />
    <img src="https://ik.imagekit.io/b2twgpcgqmc/DSDelivery/screen1_-o_U2yYtH.jpg" height="480" width="240" />
    <img src="https://ik.imagekit.io/b2twgpcgqmc/DSDelivery/screen2_h7wsJlJ6v.jpg" height="480" width="240"/>
    <img src="https://ik.imagekit.io/b2twgpcgqmc/DSDelivery/screen3_EYjWAcQfC.jpg" height="480" width="240"/>
</h3>

---

<h3 align="center" blank="_new">
<a href="https://eliasnepo-sds2.netlify.app"><img src="https://ik.imagekit.io/b2twgpcgqmc/Buttons/button_acessar-demonstracao__6__h9dnBPWJqT.png" /></a>
</h3>

---

## 📖 Sobre
O **DS Delivery** é um sistema de registro e entregas de pedidos desenvolvido na **Semana DevSuperior 2.0**. <a href="https://drive.google.com/file/d/1hap9i9fmjv7qI5QpAeAS8sHZJ-6fPUcE/view?usp=sharing">Acessar certificado.</a>

---

## 💻Desenvolvimento

No desenvolvimento, foi criada uma 
API com quatros métodos:

- GET /orders: retorna todos os pedidos do sistema de banco de dados que ainda estão pendentes;
- GET /products: retorna todos os produtos no banco de dados;
- POST /orders: envia as informações do pedido que o cliente fez para o banco de dados;
- PUT /orders/{id}/delivered: atualiza o status do pedido para entregue.

A API retorna os dados no formato json e o front-web, desenvolvido com o ReactJS, formata os dados e apresenta os dados dinamicamente na SPA (Single-page Application).

<h3 align="center">
<img src="https://ik.imagekit.io/b2twgpcgqmc/DSDelivery/modelo-conceitual_47zB06gZR.png" height="330" width="430" />
</h3>

---

## 🚀 Tecnologias

O projeto foi desenvolvido utilizando as seguintes tecnologias: 

- Back-end:
  - Java
  - Springboot
  - JPA com implementação Hibernate
  - Maven
  - Postman

- Front-end:
  - HTML / CSS / JS / Typescript
  - ReactJS
  - Axios

- Mobile:
    - React Native
    - Expo

- Implantação:
  - Front-end: Netlify
  - Back-end: Heroku
  - Banco de dados: PostgreSQL

---

## 📂 Como usar o projeto

## Versão web:

<a href="https://eliasnepo-sds2.netlify.app">Acessar demonstração</a>

## Mobile:

### 
- Fazer os passos a seguir
- Escanear o QR Code dentro do Expo

```bash
#Clonar o repositório para sua máquina
$ git clone https://github.com/eliasnepo/dsdeliver-sds2

#Entrar no diretório do projeto
$ cd dsdeliver

#Instalar as dependências
$ npm install

#Entrar no diretório do projeto mobile
$ cd front-mobile

#Executar a aplicação
$ npm start
```
---
Desenvolvido por Elias Nepomuceno 💻 