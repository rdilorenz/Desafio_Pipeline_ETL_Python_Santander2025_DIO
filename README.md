# ETL com IA Generativa – Ciência de Dados com Python - Santander 2025 - Corretora de Seguros.

## Sobre o Projeto

Este projeto é uma **adaptação didática** do desafio da realizado no Bootcamp **Ciência de Dados com Python - Santander 2025**, cujo objetivo foi demonstrar, de forma simples e prática, como funciona um pipeline **ETL (Extract, Transform, Load)** utilizando **Python** e **Inteligência Artificial Generativa**.

Como a API oficial (API da Santander DevWeek 2023) foi descontinuada, todo o fluxo foi **simulado**, mantendo a lógica original do desafio e focando no aprendizado.

---

## 🎯 Objetivo

Criar mensagens de marketing personalizadas para potenciais clientes de seguro de automovel, destacando a importância dos **seguros**, utilizando conceitos de **ETL** e **IA Generativa**.

---

## 🧠 O que é ETL?

ETL é um processo muito comum em **Data Science** e **Engenharia de Dados**:

- **Extract (Extração):** obter os dados de uma fonte  
- **Transform (Transformação):** processar ou enriquecer os dados  
- **Load (Carregamento):** salvar ou enviar os dados transformados  

Neste projeto, cada etapa foi feita em código Python.

---

## Fluxo ETL do Projeto

### 🔹 1. Extract (Extração)

Nesta etapa, os dados dos usuários são obtidos por meio da função `get_user()`, que **simula uma requisição GET para uma API REST**.

Os IDs dos usuários são simulados como se viessem de um arquivo CSV ou banco de dados.

---

### 🔹 2. Transform (Transformação)

Nesta etapa, os dados extraídos são enriquecidos com uma **mensagem de marketing personalizada**.

Aqui utilizamos a API da OpenAI para gerar mensagens personalizadas. Como solução didática foi utilizada uma chave fictícia da OpenAI, esta solução não exige conta nem crédito na OpenAI enquanto mantém o fluxo ETL intacto

---

### 🔹 3. Load (Carregamento)

Como a API original não está disponível, o resultado final é salvo localmente em JSON.


## Tecnologias Utilizadas

- Python 
- Google Colab
- JSON  
- Conceitos de ETL  
- IA Generativa (simulada)


## Contexto Educacional

Este projeto foi desenvolvido como prática educacional para o bootcamp  
**Ciência de Dados com Python - Santander 2025**, com foco em:

- ETL na prática
- Fundamentos de IA Generativa

---


