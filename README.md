# 📊 Análise de Raças de Gatos (Cat Breeds Dataset)

Iniciando no Kaggle.
Análise e visualização de dados utilizando Python e bibliotecas como Pandas e Matplotlib. Dataset de raças de gatos com estatísticas de imagens.

## 🐱 Sobre o Dataset

O conjunto de dados contém informações sobre diferentes raças de gatos, incluindo:

- Nome da raça
- Quantidade de imagens
- Largura e altura média das imagens
- Imagens corrompidas
- Formatos de imagem utilizados

Fonte: Dataset do Kaggle — [Cat Breeds](https://www.kaggle.com/datasets)

## 🔍 O que foi feito

- Leitura e inspeção inicial dos dados com `pandas.read_csv()`
- Verificação de valores nulos com `df.isnull()`
- Visualização das raças com mais imagens
- Exibição de uma imagem por raça (usando `IPython.display.Image`)
- Criação de gráfico de barras com `matplotlib.pyplot` para as top 10 raças
- Filtro de raças com menos de 10 imagens
- Contagem de raças com baixa quantidade de imagens

## 📌 Principais comandos utilizados

```python
df.head()                  # Exibir as primeiras linhas
df.isnull().sum()          # Contar valores nulos por coluna
df[df['image_count'] < 10] # Filtrar raças com poucas imagens
df.sort_values(...)        # Ordenar dados por coluna
plt.bar(...)               # Criar gráfico de barras


