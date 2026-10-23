# Challenge Sprint 4 — Classificação de Energia Renovável

--Integrantes (nome - RM):
-- Vinicius Molena - 571270
Matheus Caviglia Ferreira - 569638
Gabriel Vilas Boas da Silva Viana - 571603
Nathan Guilherme Werner - 572925
Gustavo Henrique Pereira Correia - 569921
Ricardo Algazi dos Santos - 569600

Dataset: Renewable Energy Production Dataset (2010–2020), Kaggle. Alvo: `Energy_Class`.
Modelo: Regressão Logística (scikit-learn). Cenários: 60/40 e 85/15 (treino/teste).

## Estrutura
- `data/Renewable_Energy_Data.csv` — base de dados
- `notebooks/challenge_sprint4.ipynb` — notebook completo (análise, modelo, métricas, discussões)
- `challenge_sprint4.py` — mesmo código em formato script
- `results/` — matriz de correlação, matrizes de confusão, métricas e relatórios gerados

## Como executar
```bash
pip install -r requirements.txt
# a base já está em data/
python challenge_sprint4.py          # ou abra o notebook em notebooks/ 
```
