<p align="center">
  <img src="Prototipo-chatbot.jpg" alt="Protótipo do Chatbot" width="600">
</p>


# 🤖 Aplicação com Chatbot de Segurança e Combate ao Assédio

## 🌟 Sobre o Projeto

Este projeto foi desenvolvido com muito cuidado e propósito por um grupo de mulheres comprometidas com a transformação social e tecnológica 💜. Nosso objetivo é oferecer uma solução que auxilie mulheres e pessoas LGBT+ em situações de risco, proporcionando suporte, acolhimento e conexão com serviços de emergência através de um chatbot inteligente e acessível.

> **Criado por**:
> - 👩‍💻 Carolina Lima  
> - 👩‍💻 Fernanda Agapito  
> - 👩‍💻 Ingrid Celestino dos Santos  
> - 👩‍💻 Jessica Aparecida Bueno  
> - 👩‍💻 Julia De Almeida Ribeiro  
> - 👩‍💻 Luciana Maria De Araújo Dos Santos

## 🚨 O Problema

Assédio e violência contra mulheres e pessoas LGBT+ são realidades alarmantes e recorrentes 😔. Muitas vezes, as vítimas não sabem como agir ou não têm acesso rápido a informações confiáveis. Nosso chatbot nasce como uma solução prática e discreta para oferecer apoio nesses momentos.

## 🎯 Público-Alvo

- 👩 Mulheres e 🏳️‍🌈 pessoas LGBT+
- 🏥 Organizações de apoio e acolhimento
- 🏛️ Governo e autoridades locais
- 👮 Órgãos de segurança pública
- ⚖️ Organizações de Direitos Humanos

## 💡 Justificativa

A tecnologia pode (e deve!) ser uma aliada no combate à violência. Um chatbot acessível por dispositivos móveis 📱 pode salvar vidas, oferecer orientação e encorajar denúncias, sendo uma ponte para o acolhimento e segurança.

---

## ✅ Funcionalidades

- 📘 **Orientações rápidas** em situações de risco ou violência
- 📞 **Lista de contatos de apoio** (polícia, centros de acolhimento, assistência jurídica e psicológica)
- 🚔 **Acionamento de emergência** via integração com APIs de comunicação
- 🧠 **Interface intuitiva e acessível** para qualquer perfil de usuário

---

## 🧱 Arquitetura com AWS
<p align="center">
  <img src="v2_Diagrama AWS.drawio.svg" alt="Diagrama AWS" width="600">
</p>


Utilizamos serviços da AWS para garantir segurança, escalabilidade e alta disponibilidade. Veja os principais componentes:

### 🧍 Interface do Usuário
- App iOS/Android 📱
- Plataformas como WhatsApp ou Telegram 💬

### 🔐Autenticação
- **Amazon Cognito**: login seguro via Google, Facebook ou SSO
- **Amazon Rekognition**: Detecção e comparação facial 

### 🗣️ Processamento Inteligente
- **Amazon Lex**: entendimento de linguagem natural
- **AWS Lambda**: lógica de negócios
- **AWS Comprehend**: análise de sentimentos e entidades

### 🗃️ Banco de Dados
- **Amazon DynamoDB**: armazenamento seguro e escalável

### 🚨 Respostas e Alertas
- **Amazon Pinpoint**: envio de alertas (SMS, e-mail, push)
- **Amazon Location**: rastreamento e localização em tempo real

### 🛡️ Segurança
- **AWS WAF** e **AWS Shield**: proteção contra ataques web e DDoS
- **Internet Gateway** e **CAF**: segurança de rede

### 📊 Monitoramento
- **Amazon CloudWatch**: métricas, logs e eventos do sistema

---

## 🛠️ Roadmap do Projeto

- 🧩 **Sprint 1**: Pesquisa e definição dos cenários
- 🤖 **Sprint 2**: Desenvolvimento do protótipo do chatbot
- 🔗 **Sprint 3**: Integração com APIs e testes iniciais

---

## 🧪 MVP - Produto Mínimo Viável

- Chatbot com orientações básicas
- Contatos úteis
- Acionamento de emergência com integração a API

---

## 🚀 Tecnologias Utilizadas

- **Amazon Web Services (AWS)**: Cognito, Lex, Lambda, DynamoDB, Comprehend, Pinpoint, Location, CloudWatch, WAF, Shield
- **Frontend**: Aplicativo Móvel (iOS/Android), WhatsApp, Telegram

---

## 🤝 Contribua com o Projeto

Quer colaborar com essa causa? Toda ajuda é bem-vinda!  
Abra uma *issue* ou envie um *pull request* com suas sugestões ou melhorias.

---

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
