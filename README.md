# Vendas da Loja Rossmann

<p align="center">
  <img width="1000" height="200" src="https://assets.fontsinuse.com/static/use-media-items/15/14401/full-2362x530/56702904/rossmann-schriftzug.jpeg3"/>
</p>

**Aviso:** O seguintes dados foram retirado do site https://www.kaggle.com/c/rossmann-store-sales/overview, a empresa existe e o projeto apresentado não tem vínculo com os resltados reais da empresa, o contexto, o CEO, e as questões de negócios existem apenas para elaboração desse contexto.


# Questão de negócio

Rossmann opera mais de 3.000 drogarias em 7 países europeus. Atualmente, os gerentes de loja da Rossmann têm a tarefa de prever suas vendas diárias com até seis semanas de antecedência. As vendas da loja são influenciadas por muitos fatores, incluindo promoções, competição, feriados escolares e estaduais, sazonalidade e localidade. Com milhares de gerentes individuais prevendo vendas com base em suas circunstâncias únicas, a precisão dos resultados pode ser bastante variada.

# Problema de Negócio

A requisição para prever as vendas diárias nas seis semanas das lojas vem diretamente do CEO, que quer prever o budget das lojas durante esse tempo. O mesmo quer fazer uma reforma das lojas e para saber um valor que possa investir nessas reformas deve se encaixar nos valores de vendas futuras.

# Planejamento da Solução

Para um planejamento adequado foi usado o método CRISP:

<p align="center">
  <img width="1000" height="500" src="https://www.researchgate.net/profile/Francisca-Oladipo/publication/341205300/figure/fig1/AS:888511267893249@1588849002362/Ten-Steps-of-the-Cross-Industry-Process-for-Data-Mining-source.jpg"/>
</p>

- Questão de negócio;
- Entendimento do negócio;
- Coleta dos dados;
- Limpeza dos dados;
- Exploração dos dados;
- Modelagem dos dados;
- Algoritimos de machine learning;
- Avaliação dos algoritmos;
- Aqui pode ser implementado um novo ciclo para melhorar o modelo e os algoritimos, ou finalizar e colocar o modelo em produção.
**Obs:** É sempre bom colocar o modelo em procução no fim do primeiro ciclo para receber feedback do time de negócio e assim melhorar os algoritomos na proxima rodada.

## Como será o caminho para a solução?

Com a coleta dos dados o primeiro passo é a limpeza desses dados. Visualizar como está os dados e criar um dataset único criando variáveis a partir das variáveis padrão.Com essas novas variáveis temos condições de implementar feature engineering que é o processo de usar o conhecimento de domínio para extrair recursos de dados brutos. Um recurso é uma propriedade compartilhada por unidades independentes nas quais a análise ou previsão deve ser feita. Para te uma base se cria hipóteses que levantam questões para análise exploratoria dos dados, que tinha objetivo de entender o negócio do ponto de vista dos dados e o sentimento de quais variáveis seria mais importante para o modelo.
Essas variáveis importantes que dita o passo para feacture selection que abre o caminho para rodar o Boruta, que é um método de seleção de recursos totalmente relevante. Ele tenta capturar todos os recursos importantes e interessantes que você possa ter em seu conjunto de dados com relação a uma variável de resultado.
Depois dessa modelagem é onde entra o MACHINE LEARNING, implementamos 5 algoritmos onde um é um baseline, 2 lineares e 2 não lineares para medir a complexidade dos dados. Implementamos o cross validation para fazer a medição real da performance de cada um.
E por fim avaliação do modelo ou algoritmo para ver quanto isso impacta no negócio a partir dos resultados pelo modelo (MAE, MAPE, RMSE)


## Tabelas



## Resultado


##  Modelo


## Modelo Final


#  Conclusão

#  Próximos Passos



