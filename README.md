
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-Local%20LLM-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Qwen-2.5%203B-7C3AED?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tool--Calling-Agent-blue?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Infra-Diagnóstico-6B7280?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SLA-Monitoramento-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge" />
</p>
# FatecJarvis

Projeto desenvolvido para a disciplina de **Interação Humano Computador (IHC)** da FATEC.

O objetivo do projeto é desenvolver gradualmente um **agente conversacional orientado a dados**, capaz de interagir com um sistema de tickets e realizar diagnósticos de infraestrutura de forma inteligente.

---

## Acesse o Projeto

📎 **Executar no Google Colab:**  
👉 [Abrir FatecJarvis no Colab](https://colab.research.google.com/drive/1VLMGVGQ4JPx4y3O7My3mtgQr0Z05yzab?usp=sharing)

---

## Sobre o Projeto

O FatecJarvis simula um ambiente corporativo com:

- Sistema de tickets (Service Desk)
- Monitoramento de SLA
- Análise de tickets críticos
- Diagnóstico de infraestrutura (DNS, HTTP, latência, porta 443)
- Integração com modelo LLM via Ollama
- Function Calling (Tools)

O agente é capaz de:

- 📋 Listar tickets abertos
- 🚨 Identificar tickets críticos
- 👤 Detectar tickets sem responsável
- ⏳ Calcular SLA restante
- 🌐 Executar diagnóstico do sistema e infraestrutura
- 📊 Fornecer visão geral operacional

---

## 🏗 Arquitetura

O sistema é composto por:

- Banco SQLite
- Sistema de tools (function calling)
- Camada de agente conversacional
- Diagnóstico de infraestrutura
- Seed de dados simulando ambiente real

---

## 📌 Tecnologias Utilizadas

- Python
- SQLite
- Requests
- Socket
- Ollama (LLM local)
- Google Colab

---

## 👥 Participantes

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/Templasan.png" width="120px" style="border-radius: 50%;" /><br>
      <strong>João Victor dos Reis Santos</strong><br><br>
      <a href="https://github.com/Templasan"> GitHub </a> •
      <a href="https://linkedin.com/in/joaodreissantos"> LinkedIn </a>
    </td>
  </tr>
  
</table>

</div>



---

## 📄 Licença

Projeto acadêmico desenvolvido para fins educacionais.
