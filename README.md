# Análise de Compras Públicas com Python

Este projeto realiza uma análise exploratória de dados de compras públicas, utilizando bases de licitações e contratos extraídas do Portal da Transparência.

## Objetivo

O objetivo do projeto é aplicar Python para limpar, tratar e analisar dados públicos, gerando indicadores sobre processos licitatórios, contratos, fornecedores, modalidades, categorias de contratação e valores contratados.

## Contexto

Os arquivos originais foram extraídos em formato CSV e apresentavam inconsistências comuns em relatórios públicos, como cabeçalhos repetidos, linhas institucionais, campos vazios e dados em formato textual.

Para resolver isso, foi criada uma rotina automatizada em Python para estruturar as bases antes da análise.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Etapas do projeto

1. Importação dos arquivos brutos;
2. Visualização da estrutura original dos dados;
3. Limpeza automatizada das bases;
4. Tratamento de datas e valores monetários;
5. Padronização de textos;
6. Criação de categorias por palavras-chave;
7. Análise exploratória dos dados;
8. Geração de indicadores;
9. Visualização dos resultados;
10. Exportação das bases tratadas.

## Indicadores analisados

- Total de licitações;
- Total de contratos;
- Valor total contratado;
- Valor médio dos contratos;
- Licitações por ano;
- Licitações por modalidade;
- Situação dos processos;
- Valor contratado por categoria;
- Top fornecedores por valor contratado;
- Evolução mensal das licitações.

## Estrutura do projeto

```text
analise-compras-publicas-python/
│
├── dados/
│   ├── licitacoes.csv
│   └── contratos.csv
│
├── notebook/
│   └── analise_compras_publicas.ipynb
│
├── dados_tratados/
│   ├── licitacoes_tratadas.csv
│   ├── contratos_tratados.csv
│   └── base_integrada_compras_publicas.csv
│
├── imagens/
│   ├── licitacoes_por_ano.png
│   ├── licitacoes_por_modalidade.png
│   ├── valor_por_categoria.png
│   └── top_fornecedores.png
│
└── README.md
