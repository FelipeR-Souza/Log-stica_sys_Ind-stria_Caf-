# ☕📦 Sistema de Logística para Indústria de Café

![Badge Status](https://img.shields.io/badge/STATUS-EM%20PRODU%C3%87%C3%83O-green)
![Badge License](https://img.shields.io/badge/LICEN%C3%87A-MIT-blue)

Solução integrada para otimização da cadeia logística no segmento cafeeiro, desenvolvida para reduzir custos operacionais e aumentar a precisão no controle de inventário.

## 📌 Visão Geral

Sistema completo para gestão de:
- Controle de estoque multi-armazém
- Rastreamento de lotes
- Análise preditiva de demanda

## 🚀 Tecnologias Utilizadas

| Componente       | Tecnologia                  |
|------------------|-----------------------------|
| Backend          | Google Apps Script (JavaScript) |
| Frontend         | HTML5                       |
| Banco de Dados   | Google Sheets (JSON API)    |
| Integrações      | Google Drive API, Gmail API |

## ⚙️ Funcionalidades

### 📦 Controle de Estoque
- Monitoramento em tempo real com atualização a cada 15min
- Alertas automáticos para estoque crítico
- Histórico de movimentação por lote/fornecedor

### 🚚 Módulo de Entregas
- Roteirização inteligente de entregas
- Cálculo automático de frete
- Integração com Google Maps API

### 📊 Business Intelligence
- Painel administrativo com:
  - Gráficos de sazonalidade
  - Análise ABC de produtos
  - Previsão de demanda (média móvel)

## 🛠️ Configuração

### Pré-requisitos
- Conta Google Workspace
- Google Sheets com estrutura padrão
- Acesso à Google Cloud Platform para ativar APIs

### Instalação
```bash
# Clone o repositório
git clone https://github.com/seuuser/logistica-cafe.git

# Importe para o Google Script:
1. Acesse script.google.com
2. Arquivo > Importar > Selecione todos os arquivos .gs
3. Defina os triggers em Edit > Current project's triggers
