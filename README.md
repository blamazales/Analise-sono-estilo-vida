# Análise Saúde do Sono e Estilo de Vida

📌 Contexto

Este desafio tem como objetivo analisar o impacto do estilo de vida na qualidade do sono, aplicando conceitos de frequência e medidas estatísticas. Os dados utilizados são fictícios e abrangem informações de 373 pessoas, considerando 12 características individuais para cada uma delas. Este exercício faz parte de uma atividade prática para desenvolver habilidades de análise de dados em contextos de pesquisa.

📂 O conjunto de dados contém informações sobre o estilo de vida e a saúde de 373 pessoas, com o objetivo de analisar fatores que impactam a qualidade do sono. A seguir, uma descrição das colunas:

📝 Variáveis

● Identificador – ID único de cada participante.

● Gênero – Gênero do participante (Masculino ou Feminino).

● Idade – Idade do participante em anos.

● Altura – Altura do participante em centímetros.

● Peso – Peso do participante em quilogramas.

● Profissão – Área de atuação profissional.

● Duração do sono – Quantidade média de horas dormidas por noite.

● Qualidade do sono – Avaliação subjetiva da qualidade do sono.

● Pressão sanguínea – Medida da pressão arterial no formato Sistólica/Diastólica.

● Frequência cardíaca – Número de batimentos cardíacos por minuto.

● Passos diários – Quantidade média de passos dados por dia.

● Categoria IMC – Classificação do Índice de Massa Corporal (ex: Normal, Sobrepeso, Obesidade).


⚙️ Processamento de Dados

As seguintes etapas foram aplicadas ao conjunto de dados:

1. **Processamento e Limpeza**: Corrigimos o nome de algumas colunas para padronizar o conjunto de dados, garantindo maior clareza nas análises. As alterações incluíram a tradução e ajuste de termos como "Categoria BMI" para "Categoria IMC" e a correção de "Pressão sanguíneaaaa".
2. **Análise Estatística**: Calculamos medidas de tendência central (média, mediana e moda) para a duração do sono entre diferentes profissões, analisamos a prevalência de obesidade entre engenheiros de software e investigamos a relação entre profissão e quantidade de sono.
3. **Subconjuntos e Agrupamentos**: Criamos subconjuntos de dados focados em informações específicas, como Identificador, Gênero, Idade, Pressão sanguínea e Frequência cardíaca, além de comparar métricas entre diferentes grupos de participantes (por exemplo, homens vs. mulheres na pressão sanguínea média).
4. **Cálculos Específicos**: Analisamos, entre outros pontos, quem realiza mais passos diários com base na frequência cardíaca e qual profissão é menos frequente no conjunto de dados.


📊 Análises e Visualizações

Utilizamos as bibliotecas pandas, numpy, matplotlib e seaborn para explorar o conjunto de dados. Algumas das análises realizadas incluem:

- Alteração e padronização dos nomes das colunas para facilitar a leitura.

- Cálculo de média, mediana e moda das horas de sono por profissão.

- Identificação da porcentagem de obesidade entre engenheiros de software.

- Comparação de duração média de sono entre diferentes profissões.

- Subconjunto dos dados focado em informações de saúde como pressão sanguínea e frequência cardíaca.

- Análise da pressão arterial média entre homens e mulheres.

- Verificação de padrões de sono predominantes entre os participantes.

- Avaliação da relação entre frequência cardíaca e número de passos diários.


## Tecnologias Utilizadas

- Python: Linguagem de programação utilizada para análise dos dados.

- Pandas: Para manipulação, limpeza e análise de dados.

- NumPy: Para cálculos e funções estatísticas.

- Seaborn e Matplotlib: Para criação de gráficos e visualizações.

- SciPy: Para operações estatísticas complementares.
