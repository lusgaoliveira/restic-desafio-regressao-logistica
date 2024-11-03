<div style = "text-align: center">
    
# Desafio: Classificação de Risco de Crédito com Regressão Logística 
</div>

## Objetivo do Desafio: 

Imagine que você é responsável pela análise de crédito em uma instituição financeira. Cada decisão de concessão de crédito envolve riscos, e sua missão é utilizar dados históricos para prever se um novo solicitante de crédito apresenta risco de inadimplência. Para isso, você desenvolverá um modelo preditivo utilizando técnicas de machine learning, focando em regressão logística. Este desafio não só ajudará você a aplicar conceitos fundamentais de ciência de dados e machine learning, mas também proporcionará uma compreensão prática de como modelos preditivos podem ser utilizados em decisões financeiras críticas.  A base de dados contém as seguintes variáveis para cada indivíduo: 

- **idade:** Idade da pessoa.
- **Renda:** Renda anual da pessoa. 
- **Propriedade da Casa:** Se a pessoa possui casa própria ou não. 
- **Comprimento do Emprego:** Tempo de emprego atual em anos. 
- **Intenção do Empréstimo:** Motivo pelo qual o empréstimo foi solicitado 
(ex: pessoal, educacional, compra de veículo). 
- **Grau de Empréstimo:** Categoria de classificação do empréstimo (ex: A, 
B, C...). 
- **Montante do Empréstimo:** Valor total do empréstimo solicitado. 
- **Taxa de Juros do Empréstimo:** Taxa de juros aplicada ao empréstimo. 
- **Status do Empréstimo:** Status atual do empréstimo (ex: pago, em 
atraso). 
- **Renda Percentual do Empréstimo:** Percentual da renda comprometida 
com o empréstimo. 
- **Inadimplência da Pessoa:** Histórico de inadimplência do indivíduo. 
- **Comprimento da História de Crédito:** Duração do histórico de crédito 
do indivíduo.

## Dados: 
Faça o Download em Dados: Credit Risk Dataset [Credit Risk Dataset (kaggle.com)](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)

## Tarefas:

**1. Análise Exploratória de Dados:**

- Examine as distribuições de cada variável e identifique possíveis 
correlações entre as variáveis e o risco de inadimplência. 
- Verifique e trate valores ausentes, outliers, e considere a 
transformação de variáveis categóricas em numéricas, se 
necessário. 


**2. Preparação dos Dados:**

- Divida os dados em conjuntos de treino e teste para validar o 
modelo.
- Normalize ou padronize as variáveis numéricas para garantir que 
todas as características estejam na mesma escala, o que é 
especialmente importante para a Regressão Logística.
- Realize codificação para variáveis categóricas, utilizando técnicas 
como One-Hot Encoding. 



**3. Avaliação do Modelo:**

- Utilize a Regressão Logística para construir o modelo de 
classificação.
- Ajuste o modelo utilizando os dados de treino e explore a 
importância de cada variável. 



**4. Avaliação do Modelo:**

Avalie o desempenho do modelo utilizando as seguintes métricas: 

- Acurácia: Para medir a proporção de previsões corretas. 
- Matriz de Confusão: Para visualizar a distribuição dos acertos e erros por categoria.
- Precision, Recall e F1-Score: Para avaliar o desempenho por classe de risco. 

Opcional: 
- ROC-AUC: Para entender a capacidade do modelo em distinguir entre as classes. 



**5. Interpretação dos Resultados:**

- Interprete os coeficientes do modelo para identificar as variáveis que mais impactam a probabilidade de inadimplência.. 
- Analise os resultados das métricas de avaliação e identifique pontos fortes e fracos do modelo.
- Discuta como os resultados podem ser utilizados para melhorar as políticas de concessão de crédito. 


**6. Melhorias (Opcional):**

- Explore a possibilidade de balanceamento das classes, caso a distribuição de inadimplentes e não inadimplentes esteja desbalanceada.
- Tente incluir interações entre variáveis ou crie variáveis derivadas para aprimorar o modelo.
- Realize uma análise de sensibilidade para entender como  variações nas características dos indivíduos afetam a probabilidade de inadimplência. 


## **Entrega:**

- Envie um notebook contendo todo o procedimento de análise, desde a importação dos dados até a interpretação dos resultados.
- Inclua gráficos, tabelas e comentários minuciosos acerca das descobertas e possíveis recomendações a partir dos resultados do modelo