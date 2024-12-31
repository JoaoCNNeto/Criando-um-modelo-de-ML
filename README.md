#Python para Finanças - Detecção de Fraudes

1.Importação dos Dados: Os dados de transações de cartões de crédito foram importados para análise. A base de dados contém 12 colunas, sendo 11 características das transações e uma coluna indicando se a transação é fraudulenta ou não.

2.Dicionário de Dados: As colunas incluem informações como sexo, cidade, estado, profissão do titular do cartão, categoria do comerciante, valor da transação, data e hora da transação, e um indicador de fraude.

3.Modelo de Detecção de Fraudes: Foi utilizado o método de regressão logística para modelar a relação entre as características das transações e a variável alvo (indicador de fraude).

4.Transformação dos Dados: As variáveis categóricas foram convertidas em formato numérico usando One Hot Encoding, e as variáveis numéricas foram normalizadas utilizando o StandardScaler.

5.Pipeline de Transformação e Modelo: Um pipeline foi criado para aplicar as transformações e implementar o modelo de regressão logística.

6.Treinamento e Teste do Modelo: Os dados foram divididos em conjuntos de treino e teste. O modelo foi treinado com os dados de treino e testado com os dados de teste, alcançando uma acurácia de aproximadamente 85%.

7.Teste com Transação Fraudulenta: O modelo foi testado com uma transação específica para verificar se conseguia identificar corretamente uma fraude.
