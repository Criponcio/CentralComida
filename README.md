# 🥞 Central Comida
<!-- direitos trans sao direitos humanos 🏳️‍⚧️ -->

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



* 🍽️ Encontrar receitas com base nos ingredientes selecionados.
* 📋 Visualizar os ingredientes necessários para cada receita.
* 👨‍🍳 Consultar o modo de preparo das receitas.
* 🥕 Selecionar os ingredientes disponíveis.
* ⭐ Possibilidade de favoritar receitas.
* 🔎 Buscar receitas de forma rápida.
* ↔️ Substituição de ingredientes para maior liberdade criativa.
* 📱 Interface simples e intuitiva.

---

## Diagramas de sequência e de caso de uso

```mermaid
sequenceDiagram
    actor Usuario as  Usuário
    participant App as  Frontend
    participant API as  Backend
    participant BD as  Banco de Dados

    Usuario->>App: Acessa o aplicativo
    App-->>Usuario: Exibe tela inicial

    Usuario->>App: Seleciona ingredientes
    App-->>Usuario: Exibe ingredientes selecionados

    Usuario->>App: Solicita busca de receitas
    App->>API: Envia ingredientes selecionados

    API->>BD: Consulta receitas compatíveis
    BD-->>API: Retorna receitas encontradas

    API-->>App: Retorna lista de receitas
    App-->>Usuario: Exibe receitas compatíveis

    Usuario->>App: Seleciona uma receita
    App->>API: Solicita detalhes da receita

    API->>BD: Consulta detalhes
    BD-->>API: Retorna ingredientes e preparo

    API-->>App: Retorna detalhes da receita
    App-->>Usuario: Exibe receita e modo de preparo
```
---

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
## 🌐Interfaces
<img width="2495" height="816" alt="image" src="https://github.com/user-attachments/assets/602de8f8-e63e-49d2-baf4-3d160ac31c42" />

<img width="810" height="805" alt="image" src="https://github.com/user-attachments/assets/7896781e-8f0f-443e-ad0f-fa65a6674f07" />

<img width="2494" height="815" alt="image" src="https://github.com/user-attachments/assets/3173dd2d-5390-4148-af74-0f9a867c3850" />
(interfaces ainda em andamento)

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

- [ ] **1: Alinhamento, Design e Base do Projeto**  
  * Definição dos requisitos, criação do protótipo no Figma, estruturação do projeto, modelagem do banco de dados e cadastro do conteúdo inicial de receitas e ingredientes.
- [ ] **2: Núcleo do Aplicativo**  
  * Desenvolvimento da tela inicial, catálogo de ingredientes, seleção dos ingredientes disponíveis e implementação do sistema de busca e filtragem de receitas.
- [ ] **3: Sistema de Receitas**  
  * Implementação da exibição das receitas encontradas, detalhes dos ingredientes necessários, modo de preparo, tempo de preparo e indicação de compatibilidade com os ingredientes selecionados.
- [ ] **4: Experiência do Usuário**  
  * Implementação de favoritos, filtros por categorias e melhorias na navegação, além de ajustes de UI/UX para tornar a descoberta de receitas mais rápida e intuitiva.
- [ ] **5: Testes e Lançamento do MVP**  
  * Realização de testes funcionais, correção de bugs, validação do fluxo principal, polimento da interface, documentação e publicação da primeira versão do sistema.
---
## Metodologia

* **Kanban**
  : Pela facilidade de compreender as adições necessárias ao site.
* **Espiral**
  : Pela eficácia de resolver problemas já existentes no projeto.
---

## 👥 Equipe

João Vítor Maia
