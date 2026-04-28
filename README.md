
# 🌐 Banco de Dados em Grafo – Rede Social Interativa (Neo4j)

## 📌 Visão Geral
Este projeto consiste na criação de um **banco de dados orientado a grafos**, utilizando o **Neo4j**, para modelar uma **rede social interativa**.

O objetivo é representar usuários, conexões sociais e interações de forma eficiente, explorando o potencial dos grafos para análise de relacionamentos, recomendações e navegação social.

---

## 🧠 Por que Neo4j?
Bancos de dados em grafo são ideais para cenários onde o **relacionamento entre os dados é tão importante quanto os próprios dados**, como:
- Redes sociais
- Sistemas de recomendação
- Análise de comunidades
- Detecção de padrões e conexões

O Neo4j utiliza a linguagem **Cypher**, que permite consultas intuitivas e altamente performáticas sobre grafos.

---

## 🛠️ Tecnologias Utilizadas
- **Neo4j**
- **Cypher Query Language**
- Neo4j Browser / Neo4j Desktop

---

## 🧩 Modelo de Dados

### 🧑 Nós (Nodes)
- `Usuario`
  - id
  - nome
  - idade
  - cidade
  - interesses

### 🔗 Relacionamentos (Relationships)
- `(:Usuario)-[:AMIGO_DE]->(:Usuario)`
- `(:Usuario)-[:SEGUE]->(:Usuario)`
- `(:Usuario)-[:CURTIU]->(:Post)`
- `(:Usuario)-[:COMENTOU]->(:Post)`

---
