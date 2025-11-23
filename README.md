# Modelagem da Distribuição Populacional dos Municípios Brasileiros: uma Comparação entre Pareto e Modelos Alternativos

Projeto de análise de dados referente à distribuição das populações dos municípios brasileiros.

**Objetivo:** avaliar se a distribuição de Pareto se adequa a cauda dos dados, e como ela se compara com outras distribuições (log-normal e lei de potência com truncamento exponencial).

**Ferramentas:** arquivo Jupyter Notebook com linguagem Python e biblioteca "power law" (https://github.com/jeffalstott/powerlaw).

**Datasets:** arquivos em formato .csv referentes aos anos de 2025, 2024, 2021 e 2020. Eles foram tratados pelo autor no Excel a partir das estimativas do IBGE disponibilizadas em:
https://www.ibge.gov.br/estatisticas/sociais/populacao/9103-estimativas-de-populacao.html?edicao=44309

**Instruções:** definir o ano da análise alterando a segunda célula do arquivo Jupyter Notebook, e executar o código.

**Resultados:** o código retorna a cauda de dados que melhor se ajusta à lei de potência, os parâmetros das distribuições ajustadas, os _log-likelihood ratio tests_ para comparação do ajuste das distribuições, além de gráficos e tabelas que auxiliam na análise.
