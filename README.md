# 📊 Retail Case – EDA

Este repositório apresenta uma análise exploratória de dados (EDA) aplicada ao setor varejista. O objetivo é entender o comportamento de clientes com base em dados demográficos, consumo e histórico de campanhas, a fim de identificar padrões relevantes e oportunidades estratégicas.

##  Objetivo

Explorar um conjunto de dados de clientes do varejo para:

* Avaliar o perfil demográfico dos consumidores
* Analisar a aceitação de campanhas de marketing
* Entender o consumo de produtos premium
* Identificar padrões de comportamento para segmentações mais eficazes

##  Tecnologias utilizadas

* Python 3.10+
* Jupyter Notebook
* Pandas
* Matplotlib / Seaborn
* Plotly (opcional)
* NumPy

## 📂 Estrutura do projeto

```
📁 Retail Case - EDA
│
├── Retail Case- EDA.ipynb   # Notebook principal com toda a análise
├── README.md                # Este arquivo
└── data/                    # (Opcional) Pasta com dataset, se aplicável
```

##  Principais análises realizadas

*  **Distribuição de Respostas por Faixa Etária**

  * Faixas entre 41–60 anos têm maior volume de respostas absolutas
  * A maior **taxa de aceitação proporcional** está na faixa de 21–30 anos

*  **Histórico de Campanhas Aceitas**

  * Análise dos campos `AcceptedCmp1` a `AcceptedCmp5` e `Response`

*  **Consumo de Produtos Premium**

  * Avaliação do consumo de vinhos, frutas, carnes, peixes, doces e ouro

*  **Perfil Familiar**

  * Relações entre status civil, número de filhos e engajamento com campanhas

##  Como executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/retail-case-eda.git
   cd retail-case-eda
   ```

2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook:

   ```bash
   jupyter notebook "Retail Case- EDA.ipynb"
   ```

##  Conclusão

A análise revelou perfis de maior engajamento com campanhas e padrões de consumo relevantes para decisões de marketing. O foco em proporções evitou interpretações enviesadas, trazendo mais clareza na identificação de grupos-alvo.

