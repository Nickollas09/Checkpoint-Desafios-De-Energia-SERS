# Checkpoint-Desafios-De-Energia-SERS

## Análise de Dados de Energia com API Pública do ONS

Projeto desenvolvido para a disciplina de **Soluções em Energias Renováveis e Sustentáveis** do curso de **Ciência da Computação**. 

O objetivo é analisar o comportamento da carga elétrica no Sistema Interligado Nacional (SIN), utilizando dados reais consumidos via API pública do Operador Nacional do Sistema Elétrico (ONS).

---

## Visão Geral do Projeto

Este estudo realiza a extração, tratamento e análise da carga elétrica verificada no estado de São Paulo (área `SP`) durante o período de **01/08/2025 a 07/08/2025**. 

A partir do consumo da API em formato JSON, a aplicação consolida a estrutura de dados para cálculo de indicadores de demanda, análise de padrões temporais e geração de relatórios gráficos de suporte à tomada de decisão no planejamento energético.

---

## Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Requisições HTTP:** `requests`
- **Manipulação de Dados:** `pandas`
- **Visualização de Dados:** `matplotlib`
- **Ambiente de Desenvolvimento:** Jupyter Notebook / Google Colab

---

## Estrutura e Métricas da API

Os dados consultados contêm 336 registros temporais e cobrem as seguintes métricas principais:

- `val_cargaglobal`: Carga elétrica global medida no período
- `val_cargasupervisionada`: Carga sob supervisão direta do sistema
- `val_cargammgd`: Carga referente à Micro e Minigeracão Distribuída (MMGD)
- `din_referenciautc` / `dat_referencia`: Timestamp e data de medição

---

## Links do google colab
- https://colab.research.google.com/drive/1FPBrJ5Tx9KUw_fDdLiN0QIAfn9_hxEaA?usp=sharing
- https://colab.research.google.com/drive/10N9wK9WbXWA6XKqHK7E6DrA7r6eTwDXj?usp=sharing
