# Análise de Dados — SERS

## Grupo:

Andrey Crence Fernandes - RM 573840

Giulliana Maistro Brasolin - RM 569381

Mikaella Mirela Dos Santos Lucindo - RM 573775

Lara Dos Santos Cândido Alves - RM 573827

Lucas Parkin Devito - RM 573251

## Descrição da atividade

Repositório com as atividades práticas da disciplina **Soluções em Energias Renováveis e Sustentáveis**, aplicando Orange Data Mining, Python e Pandas na preparação, inspeção e análise de conjuntos de dados do setor elétrico.


O trabalho está dividido em duas etapas:

1. **Exercícios com datasets de energia** — preparação, inspeção e análise de seis conjuntos de dados diferentes do setor elétrico (consumo residencial, industrial, geração solar/eólica etc.), utilizando Orange Data Mining para a etapa exploratória inicial e Python/Pandas para os cálculos, filtros e interpretações.
2. **Desafio final — Análise de dados de energia com API pública** — consulta a uma API pública em tempo real, construção de um DataFrame a partir do JSON retornado, cálculo de indicadores, geração de gráficos e elaboração de um relatório técnico com apoio de IA (Gemini), incluindo validação crítica do texto gerado.

## Arquivos

| Arquivo | Descrição |
|---|---|
| `SERS_CP01.ipynb` | Exercícios com os seis datasets de energia (preparação, filtros, indicadores e interpretações) |
| `Desafio_Final_Energia_ONS_API_Colab.ipynb` | Desafio final com consulta à API do ONS, indicadores, gráficos e relatório técnico com IA |

## Fontes dos dados analisados

### Exercícios com datasets de energia

| Dataset | Fonte | Link |
|---|---|---|
| Appliances Energy Prediction | UCI Machine Learning Repository | https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction |
| Steel Industry Energy Consumption | UCI Machine Learning Repository | https://archive.ics.uci.edu/dataset/851/steel+industry+energy+consumption |
| Power Consumption of Tetouan City | UCI Machine Learning Repository | https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city |
| Solar Power Generation Data | Kaggle | https://www.kaggle.com/datasets/anikannal/solar-power-generation-data |
| Wind & Solar Energy Production Dataset | Kaggle | https://www.kaggle.com/datasets/ahmeduzaki/wind-and-solar-energy-production-dataset |
| Individual Household Electric Power Consumption | UCI Machine Learning Repository | https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption |

### Desafio final — Carga elétrica

- **Fonte:** API pública de Carga Verificada do Operador Nacional do Sistema Elétrico (ONS)
- **Portal:** https://dados.ons.org.br/
- **Conjunto de dados:** https://dados.ons.org.br/dataset/carga-energia-verificada
- **Recorte utilizado:** área SP — São Paulo, período de 01/08/2025 a 07/08/2025

## Ferramentas utilizadas

- Orange Data Mining (preparação e amostragem inicial dos dados)
- Python (Pandas, Matplotlib, Requests)
- Google Colab
- API Gemini (apoio na geração do relatório técnico do desafio final)
