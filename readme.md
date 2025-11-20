# 🔮 Aura - Assistente Financeiro Inteligente

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=MVP%20&color=GREEN&style=for-the-badge)
![Badge IBM](https://img.shields.io/badge/IBM%20Cloud-watsonx-blue?style=for-the-badge&logo=ibm)
![Badge Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

> "O futuro do atendimento financeiro: eficiência tecnológica com empatia digital."

## 📄 Sobre o Projeto
O **Aura** é uma solução de chatbot inteligente desenvolvida para automatizar o atendimento ao cliente em instituições financeiras. Utilizando a tecnologia **IBM watsonx Assistant**, o Aura é capaz de compreender linguagem natural (NLP), resolver solicitações de segunda via de boletos e integrar-se a sistemas de backend para consultas em tempo real.

O objetivo é reduzir em até 80% a carga de atendimentos humanos repetitivos, oferecendo suporte 24/7.

---

## 🛠️ Tecnologias Utilizadas

* **Frontend:** HTML5, JavaScript (Vanilla), Tailwind CSS (via CDN).
* **Inteligência Artificial:** IBM watsonx Assistant (NLP e Dialog Flow).
* **Integração:** IBM Cloud Web Chat Integration.
* **Arquitetura (Planejada):** Node.js (API Gateway) e IBM Db2 (Banco de Dados).

---

## 🏗️ Arquitetura da Solução

O projeto segue uma arquitetura de microsserviços dividida em 4 camadas:

1.  **Interface (Frontend):** Landing page responsiva que mantém o contexto da sessão do usuário.
2.  **Orquestrador (Watson):** Gerencia o diálogo e identifica as intenções do usuário (Ex: `#fatura_vencida`).
3.  **API Gateway:** Camada de segurança e regras de negócio (simulada via Webhook neste MVP).
4.  **Dados:** Base de informações de clientes e faturas.

---

## 🚀 Como Rodar o Projeto

Este projeto é um Frontend estático integrado à nuvem da IBM. Não requer instalação de dependências locais (Node_modules).

### Pré-requisitos
* Navegador Web moderno (Chrome, Edge, Firefox).
* Conexão com a internet (para carregar o Tailwind e o Chatbot).

### Passo a Passo
1.  Clone este repositório:
    ```bash
    git clone [https://github.com/SEU-USUARIO/aura-chatbot.git](https://github.com/SEU-USUARIO/aura-chatbot.git)
    ```
2.  Navegue até a pasta do projeto.
3.  Abra o arquivo `index.html` no seu navegador.
4.  Interaja com a **Aura** no canto inferior direito!

---

## 🧪 Casos de Uso (Demo)

Para testar o fluxo principal do MVP, utilize as seguintes frases no chat:

* *"Minha fatura venceu ontem"*
* *"Quero pagar meu boleto"*
* *"Preciso de ajuda com a conta"*

---

## 👥 Autores

* **Denise Shamira**
* **Paulo**
* **Gabriel**

---

Made with 💜 and IBM Cloud.