# Indicadores Macro Brasil

Análise exploratória de indicadores macroeconômicos brasileiros (IPCA, câmbio USD/BRL e Selic), com dados extraídos diretamente da API do Banco Central (SGS).

## Objetivo
Projeto de estudo aplicado, parte da minha transição de carreira para Análise de Dados/Finanças. Serve de base para conteúdo publicado no LinkedIn.

## Gráfico

![IPCA, Câmbio e Selic desde 2020](outputs/grafico-ipca-cambio.png)

## Como rodar
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab notebooks/ipca_cambio.ipynb
```

## Estrutura
- `notebooks/ipca_cambio.ipynb` — coleta, exploração e visualização dos dados
- `outputs/` — gráficos gerados

## Fonte de dados
- Banco Central do Brasil — Sistema Gerenciador de Séries Temporais (SGS)
  - IPCA (série 433), Câmbio USD/BRL venda (série 1), Selic meta (série 432)