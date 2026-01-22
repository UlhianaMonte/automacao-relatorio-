# automacao-relatorio-
Lê Excel - Limpa dados - Gera relatório

import pandas as pd

df = pd.read_excel("dados.xlsx")
df = df.dropna()
df.to_excel("relatorio_final.xlsx", index=False)
