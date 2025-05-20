# Análise de Churn de Clientes

Este projeto tem como objetivo analisar o comportamento de clientes de uma empresa para prever a evasão (churn), utilizando ferramentas de ciência de dados e aprendizado de máquina.

## Objetivo

Entender os principais fatores que influenciam o churn de clientes, com base em dados históricos, para auxiliar na tomada de decisões estratégicas da empresa.

## Estrutura do Projeto

- `dataset/`: arquivos CSV com os dados brutos e tratados.
- `notebooks/`: notebooks com etapas de limpeza, análise exploratória, correlação de variáveis e modelagem.
- `models/`: modelos treinados e scripts de machine learning.
- `visualizations/`: gráficos gerados nas análises.
- `README.md`: explicações gerais do projeto.

## Como Executar o Projeto no Google Colab

Para facilitar o acesso, o projeto pode ser executado diretamente no navegador utilizando o Google Colab. Siga os passos abaixo:

1. **Acesse o Google Colab:**
   - https://colab.research.google.com/

2. **Abra o notebook do projeto:**
   - Clique na aba `Arquivo` > `Abrir notebook`
   - Selecione a aba `GitHub` e cole a URL do repositório (exemplo abaixo):
     ```
     https://github.com/seu-usuario/seu-repositorio
     ```
   - Escolha o notebook principal, como `analise_churn.ipynb`.

3. **Carregue o dataset:**
   - Clique no ícone de pasta à esquerda (`Arquivos`).
   - Faça o upload do arquivo CSV do dataset, se necessário.
   - Ou altere a célula de leitura do CSV para um link público (ex: Google Drive ou GitHub Raw).

4. **Execute as células do notebook:**
   - Clique em `Executar tudo` (ícone de play ou `Ctrl+F9`) para rodar todo o notebook.
   - As análises e visualizações serão geradas diretamente na tela.

> **Importante:** Certifique-se de estar logado em uma conta Google para salvar o progresso ou fazer cópias do notebook.

## Instalação

Clone o repositório e instale as dependências com:

```bash
pip install -r requirements.txt
