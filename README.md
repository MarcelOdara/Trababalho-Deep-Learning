# Trababalho-Deep-Learning
Trabalho Final de Deep Learning realizado por Marcel dos Santos Izidoro, Estudante da Faculdade Senac.

#  Tradutor Inteligente de Rótulos

## 📌 Sobre o Projeto
Aplicação web que traduz automaticamente os rótulos do arquivo `train.tsv` do russo para o português, utilizando a API do Google Translate e Streamlit.

##  Objetivo
Facilitar o acesso e compreensão de dados em russo para falantes de português, demonstrando aplicação prática de Deep Learning e NLP.

##  Tecnologias Utilizadas
- **Streamlit** - Interface web
- **Pandas** - Manipulação de dados
- **Requests** - API do Google Translate
- **Google Translate API** - Tradução automática

## Funcionalidades
-  Tradução individual por ID
-  Tradução em lote (até 20 registros)
-  Estatísticas do dataset
-  Exportação de resultados em CSV
-  Cache de traduções

##  Como Executar

### Pré-requisitos
```bash
pip install streamlit pandas requests
