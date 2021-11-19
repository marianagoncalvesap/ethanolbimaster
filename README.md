# Título do Trabalho

#### Aluno: [Mariana Gonçalves Almeida Pinto](https://github.com/marianagoncalvesap)
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

Em vista das perspectivas de desenvolvimento do mercado bioenergético, hoje, há uma necessidade latente de criação de métodos de acompanhamento e previsão desse mercado.

Com base nisso, o presente projeto visa por meio da aplicação de redes neurais recorrentes prever os indicadores de preços médios mensais dos biocombustíveis etanol anidro e etanol hidratado. 

Para o desenvolvimento deste estudo,  foram extraídas do site do CEPEA bases com os indicadores mensais do etanol hidratado combustível e etanol anidro combustível de São Paulo, desde 28/11/2002 até 29/06/2021 e dado que se trata de uma questão de aprendizado sequencial, a modelagem adotada foi a LSTM.

Como resultados desse estudo, foi possível observar que a assertividade do modelo é elevada quando aplicada para prever os indicadores de preços médios mensais de etanol hidratado, porém tal resultado não é tão significativo na previsão para o etanol anidro. Esse panorama de resultados pode ser exemplificado pelo R², que no primeiro biocombustível foi 0.946275837398085 e no segundo 0.7309975549736121.

### Abstract

From the perspectives of development of the bioenergy market, today, there is a strong need to create methods for monitoring and forecasting this market.

Based on this, this project aims, through the application of recurring neural networks, to predict monthly average price indicators for anhydrous ethanol and hydrous ethanol biofuels.

For the development of this study, databases with monthly indicators of fuel hydrated ethanol and anhydrous ethanol fuel in São Paulo were extracted from the CEPEA website, from 11/28/2002 to 06/29/2021 and given that this is a question of Sequential learning, the model adopted was the LSTM.

As a result of this study, it was possible to observe that the model's assertiveness is high when applied to predict the monthly average price indicators for hydrous ethanol, however such result is not as significant in the prediction for anhydrous ethanol. This panorama of results can be exemplified by the R², which in the first biofuel was 0.946275837398085 and in the second 0.7309975549736121.

### 1. Introdução

Em vista das perspectivas de crescimento do mercado de bioenergia, atualmente, há uma necessidade latente de criação de métodos de acompanhamento e previsão desse mercado.

A partir disso, este projeto tem o objetivo de a partir da aplicação de redes neurais recorrentes prever os indicadores de preços médios mensais dos combustíveis etanol anidro e do etanol hidratado.

Para a elaboração deste projeto, as bases utilizadas foram extraídas do site do CEPEA e apresentam os resultados dos indicadores mensais do etanol hidratado combustível e etanol anidro combustível de São Paulo, desde 28/11/2002 até 29/06/2021.

Ao longo do desenvolvimento deste trabalho, em vista de que se trata de uma questão de aprendizado sequencial, a modelagem adotada foi a LSTM, devido à sua eficiência como uma Gated RNN. Visando uma análise assertiva sobre os erros e ajustes do modelo, como métricas de avaliação para medir o desempenho da rede neural recorrente selecionada foram adotadas o MAPE, RMSE, R² e MSE. 

Com base nisso, portanto, o presente trabalho tem o objetivo de apresentar uma modelagem de previsão de série temporal de indicadores de preços dos biocombustíveis mencionados anteriormente para facilitar o acompanhamento, a projeção dos valores e a tomada de decisão dentro de empresas que atuam nesse mercado.

### 2. Modelagem

Em vista da natureza sequencial do objeto de estudo deste projeto, foi construída uma RNN. Esta rede neural recorrente se caracteriza por ser muito utilizada para processar dados sequenciais, devido à sua alta capacidade de flexibilidade de conexão em suas arquiteturas.





Visando uma maior eficiência na modelagem, a LSTM foi adotada junto com o otimizador Adam e o loss R².





Na etapa de Treinamento, dividimos o processo em 5 épocas e como resultado foi possível observar o seguinte:

Etanol Hidratado:
























Etanol Anidro:


























### 3. Resultados

Etanol Hidratado:

A partir da base de dados do Etanol Hidratado, foi possível observar uma correlação significativa entre o realizado e o previsto, devido aos resultados positivos apontados pelas seguintes métricas de avaliação:

R2:  0.946275837398085
MAPE:  10.569350179064738 %
MSE:  0.015494116126401128
RMSE:  0.12447536353190991















Etanol Anidro:

Por meio da base de dados do Etanol Anidro, também foi possível observar uma correlação significativa entre o realizado e o previsto, devido aos resultados indicados pelas seguintes métricas de avaliação:

R2:  0.7309975549736121
MAPE:  180.77732810217734 %
MSE:  20.707052378852655
RMSE:  4.550500233914141















### 4. Conclusões


Com base nos resultados levantados ao longo da aplicação da modelagem LSTM, foi possível observar que o mercado de bioenergia possui um grande desafio na previsão de indicadores dos preços médios mensais, dada à volatilidade do mercado e no caso do etanol, a diferença de aplicação de cada tipo do biocombustível.

Para a base de dados de etanol hidratado, a modelagem apresentou uma assertividade significativa por meio, por exemplo, do R² elevado, que foi de 0.946275837398085; do MAPE  de 10.569350179064738 %; do MSE 20.707052378852655 e RMSE 4.550500233914141.

Porém, para a base de dados de etanol anidro, tal modelagem não apresentou tal eficácia na previsão. Tal dificuldade na assertividade pode ser observada pelas mesmas métricas que apresentaram, respectivamente, os seguintes resultados 0.7309975549736121;180.77732810217734 %;20.707052378852655 e 4.550500233914141.

A partir disso, portanto, é possível concluir que para prever indicadores de preços a LSTM é uma rede neural efetiva e assertiva, porém que para um estudo mais amplo e eficaz é necessário aprofundar a análise por meio

---

Matrícula: 192.110.208

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
