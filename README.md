# Análise de vendas de videojogos

Projeto Integrado 1 do bootcamp de Análise de Dados da TripleTen, desenvolvido por Isabella Ramalho Daniel.

## Objetivo
Analisar padrões históricos de vendas para apoiar o planeamento de campanhas da loja fictícia Ice para 2017. O foco da análise recente é o período de 2013 a 2016.

## Dados
O ficheiro `games.csv`, fornecido no projeto académico da TripleTen, contém nomes de jogos, plataformas, anos de lançamento, géneros, vendas regionais, avaliações e classificações ESRB. As vendas são medidas em milhões de unidades. Os dados de 2016 podem estar incompletos.

## Ferramentas
Python, Pandas, NumPy, Matplotlib e SciPy. Desenvolvimento em Jupyter Notebook.

## Etapas
- Inspeção e preparação dos dados, incluindo tipos de colunas e valores ausentes.
- Análise das vendas e da evolução das plataformas.
- Comparação de géneros, avaliações e padrões regionais.
- Testes t de Welch para comparar avaliações de utilizadores, com significância de 5%.
- Recomendações para campanhas com base nas características de cada mercado.

## Principais conclusões
- A PS4 apresenta forte participação na América do Norte e na Europa; no recorte analisado, corresponde a cerca de 35,97% das vendas europeias.
- O Japão apresenta um perfil distinto, com destaque para a plataforma 3DS e o género Role-Playing.
- Na PS4, as notas dos críticos têm correlação positiva moderada com as vendas (aproximadamente 0,41), enquanto as notas dos utilizadores têm correlação próxima de zero. Correlação não demonstra causalidade.
- Não foi encontrada evidência suficiente de diferença entre as médias das notas de Xbox One e PC (p ≈ 0,147).
- Foi encontrada diferença estatisticamente significativa entre as médias das notas de Action e Sports.

## Como executar
1. Descarregue ou clone este repositório.
2. Instale as dependências: `python -m pip install -r requirements.txt`.
3. Na pasta do projeto, execute `jupyter notebook`.
4. Abra `analise_vendas_videojogos.ipynb` e execute as células pela ordem apresentada.

O notebook e `games.csv` devem ficar na mesma pasta.

## Limitações
Este é um estudo histórico e académico, não uma previsão do mercado atual. As vendas não permitem calcular lucro ou rentabilidade sem informação de custos e preços. Valores ausentes foram preservados quando não havia base para os preencher.

## Autora
Isabella Ramalho Daniel — [GitHub](https://github.com/ramalhoisa) | [LinkedIn](https://www.linkedin.com/in/ramalhoisa/)
