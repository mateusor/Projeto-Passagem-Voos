# 🛫 Sistema de Gerenciamento de Passagens Aéreas

Este projeto consiste em um sistema simples de gerenciamento de voos e passageiros, desenvolvido como prática da disciplina de Algoritmos de Programação na Pontifícia Universidade Católica de Campinas (PUC-Campinas).

## 👨‍💻 Integrantes

- Arthur Grizone Silvestre de Oliveira - 25008341  
- Lucas Rodrigues Xavier - 25000508  
- Mateus Oliveira Rafael - 25001369  
- Wandely Celestino Vieira Filho - 25007121  

---

## 🧩 Descrição do Projeto

O sistema foi desenvolvido com o objetivo de facilitar o gerenciamento de voos e passageiros em uma companhia aérea fictícia. É possível cadastrar voos, registrar passageiros, realizar vendas e cancelamentos de passagens, além de consultar dados de forma dinâmica e prática.

---

## 📁 Estrutura do Sistema

O sistema é baseado em três dicionários principais:

- `voos`: armazena os dados de cada voo, com código, origem, destino, número de escalas, preço e lugares disponíveis.
- `passageiros`: associa cada CPF a uma lista de voos adquiridos.
- `dados_passageiros`: armazena nome e telefone do passageiro por CPF.

---

## 🔧 Funcionalidades

- **Cadastrar Voo**
- **Consultar Voos**
  - Por código do voo
  - Por cidade de origem
  - Por cidade de destino
- **Listar Passageiros de um Voo**
- **Vender Passagem**
- **Cancelar Passagem**
- **Buscar voo com menos escalas entre duas cidades**

---

## 💡 Desafios Enfrentados

- Controle rigoroso de lugares disponíveis por voo
- Relacionamento consistente entre passageiros e múltiplos voos
- Padronização de entradas com uso de `.lower()` para evitar erros por capitalização
- Reestruturação do sistema para uso do CPF como identificador principal do passageiro

---

## 🧪 Requisitos e Execução

- **Linguagem:** Python 3.11+
- **Editor recomendado:** Visual Studio Code (VSCode) ou IDLE do Python

### Como executar:
```bash
python sistemavoosFinal.py
