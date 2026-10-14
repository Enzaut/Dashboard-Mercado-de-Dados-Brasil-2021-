# Mercado de Dados no Brasil em Números

Dashboard interativo no Tableau Public sobre o mercado de trabalho em dados no Brasil, construído a partir da pesquisa **State of Data Brazil 2021** (Data Hackers).

**Dashboard publicado:** https://public.tableau.com/app/profile/enzo.gomide.martins/viz/MercadodeDadosBrasil2021/MercadodeDadosnoBrasilemNmeros?publish=yes

## Sobre o projeto

Análise de ~2.645 respostas de profissionais de dados de todo o Brasil, buscando responder:

- Onde estão os profissionais de dados no Brasil (por estado)?
- Como o salário varia por senioridade e por cargo?
- Quais linguagens de programação são mais usadas no mercado?
- Existe relação entre satisfação no trabalho e intenção de trocar de emprego?

## Principais insights

- **São Paulo concentra a maior parte dos profissionais de dados** (1.076 dos 2.645 respondentes), seguido por Minas Gerais e Rio de Janeiro.
- **SQL e Python dominam o mercado**: usados por 56% e 51% dos profissionais, respectivamente — bem à frente de R, Java e as demais linguagens.
- **Salário cresce de forma consistente com a senioridade**, com concentração clara de Júnior nas faixas até R$4.000/mês e Sênior acima de R$8.000/mês.
- **Insatisfação é um forte preditor de busca por emprego**: 64,5% dos profissionais insatisfeitos com a empresa atual já estão buscando oportunidade, contra apenas 12,9% dos satisfeitos.

## Fonte de dados

[State of Data Brazil 2021](https://www.kaggle.com/datasets/datahackers/state-of-data-2021) — pesquisa anual da comunidade Data Hackers sobre o mercado de trabalho em dados no Brasil.

## Ferramentas utilizadas

- **Tableau Public** — construção e publicação do dashboard
- **Python** (pandas, openpyxl) — tratamento e limpeza dos dados antes da modelagem
- **Excel** — conferência e ajustes pontuais

## Estrutura do repositório

```
├── README.md
├── Diario do Projeto.txt          # processo completo: dificuldades encontradas e soluções
└── extracted/
    ├── State of Data 2021 - Dataset - Pgina1.csv   # base original (Kaggle)
    └── State of Data 2021 - Pronto para Tableau.xlsx # base tratada, usada no Tableau
```
