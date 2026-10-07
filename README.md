# 🥞 CentralComida

## 📖 Sobre o Projeto

Um site de receitas para qualquer tipo de fome, da comunidade, para comunidade.

Uma ajuda as pessoas a encontrarem receitas mais rápido, com possibilidade de selecionar quais ingredientes você possui e encontrar o que fazer com esses ingredientes.
Com você podendo ajudar a crescer as receitas disponíveis no site.

---

## 🎯 Objetivo
O principal objetivo do projeto é facilitar a descoberta de receitas a partir dos ingredientes que o usuário já possui, tornando o processo de decidir o que cozinhar mais rápido e prático.

Além disso, o projeto pode contribuir para:

* Reduzir o desperdício de alimentos.
* Aproveitar melhor os ingredientes disponíveis.
* Economizar tempo na busca por receitas.
* Incentivar as pessoas a cozinhar em casa.


## ✨ Funcionalidades

* 🔎 Buscar receitas de forma rápida.
* 🥕 Selecionar os ingredientes disponíveis.
* 🍽️ Encontrar receitas com base nos ingredientes selecionados.
* 📋 Visualizar os ingredientes necessários para cada receita.
* 👨‍🍳 Consultar o modo de preparo das receitas.
* ⭐ Possibilidade de favoritar receitas.
* 📱 Interface simples e intuitiva.


---

## ⚙️ Funcionalidades Principais


O fluxo principal da aplicação é simples:

O usuário acessa a aplicação.

Seleciona os ingredientes que possui.

A aplicação analisa as receitas disponíveis.

São apresentadas receitas que podem ser preparadas com os ingredientes selecionados.

O usuário escolhe uma receita.

A aplicação apresenta os ingredientes e o modo de preparo.


---

## Diagramas de sequência e de caso de uso

```mermaid
flowchart LR
    Usuario((👤 Usuário))

    subgraph Sistema["🍳 Sistema de Receitas"]
        UC1([Selecionar ingredientes])
        UC2([Buscar receitas])
        UC3([Visualizar receitas])
        UC4([Visualizar ingredientes])
        UC5([Visualizar modo de preparo])
        UC6([Favoritar receita])
    end

    Usuario --> UC1
    Usuario --> UC2
    Usuario --> UC3
    Usuario --> UC6

    UC1 --> UC2
    UC2 --> UC3
    UC3 --> UC4
    UC3 --> UC5
    UC6 --> UC3

```
---

## 🛠️ Tecnologias

### **Frontend**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### **Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

### **Banco de Dados**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### **API**
![REST](https://img.shields.io/badge/REST-violet?style=for-the-badge)
---

## 🗓️ Roadmap do MVP

- [ ] **Milestone 1: Alinhamento, Design e Base do Projeto**  
  * Protótipo no Figma, setup da estrutura Expo/Node.js, modelagem do PostgreSQL e criação do conteúdo inicial.
- [ ] **Milestone 2: Núcleo do Aplicativo**  
  * Login com Firebase, mapa de fases e motor visual dos 3 tipos de exercícios.
- [ ] **Milestone 3: Gamificação e Sandbox Python**  
  * Contador de Streaks, barra de progresso e integração do Pyodide (WASM) para execução de código.
- [ ] **Milestone 4: Tutor IA**  
  * Engenharia de prompts e integração da LLM para suporte dinâmico no player de exercícios.
- [ ] **Milestone 5: Testes e Lançamento**  
  * Correções de bugs, polimento de UI/UX, deploy da infraestrutura e publicação da versão de teste.
---
## Metodologia

**Kanban** : asdasdadasd12124234234234242
---

## 👥 Equipe

João Vítor Maia
