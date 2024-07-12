# desafio-ds-imdb-diel

Desafio Cientista de Dados Insidium Lighthouse

## Bibliotecas Utilizadas

- **pandas**: Manipulação e análise de dados tabulares.
- **matplotlib.pyplot**: Criação de visualizações de dados estáticas.
- **seaborn**: Geração de visualizações de dados com estilo estatístico.
- **sklearn.model_selection**: Divisão de dados em conjuntos de treinamento e teste.
- **sklearn.preprocessing**: Pré-processamento e normalização de dados.
- **sklearn.impute**: Imputação de valores ausentes.
- **sklearn.linear_model**: Implementação de modelos de regressão linear.
- **sklearn.metrics**: Cálculo de métricas de desempenho do modelo (MSE, R2).

## Instalação e Execução

**Pré-requisitos:**

- Python 3.8 ou superior
- Pip (gerenciador de pacotes Python)
- Bibliotecas:
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

**Instalação:**

1. Clone o repositório do projeto:

```bash
    git clone https://github.com/andriel300/desafio-ds-imdb-diel.git
```

2. Navegue até a pasta do projeto clonado:

```bash
    cd desafio-ds-imdb-diel
```

3. Criando ambientes virtuais (Opcional):

```shell
    python -m venv qualquernome-env
    qualquernome-env\Scripts\activate
```

4. Instale as dependências do projeto:

```bash
    pip install -r requirements.txt
```

ou utilize GitHub Desktop para clonar meu projeto.

### 1.Introdução

- Para ajudar a PProductions a decidir qual tipo de filme desenvolver a seguir, vou seguir uma abordagem estruturada, conforme descrito anteriormente, com um foco especial em fatores que influenciam o sucesso de filmes.
- Este projeto visa analisar dados de filmes do IMDB (Internet Movie Database) para identificar os principais fatores que influenciam a alta expectativa de faturamento. Através de técnicas de análise de dados e machine learning, pretende-se construir um modelo preditivo que possa estimar o potencial de sucesso de novos filmes.

- **Objetivo**: Identificar os fatores que contribuem para o sucesso de um filme e recomendar o tipo de filme que a PProductions deve desenvolver a seguir.

Métricas de Sucesso:

    Receita de bilheteria.
    Avaliações da crítica (Metacritic).
    Avaliações do público (IMDb).
