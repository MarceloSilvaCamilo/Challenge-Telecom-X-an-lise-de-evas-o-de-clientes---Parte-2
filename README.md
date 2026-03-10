# Challenge Telecom X: Previsão de Churn com Machine Learning 🤖📉

Este repositório contém a **Parte 2** do desafio de Data Science do programa **Oracle Next Education (ONE)**. Após o processo de ETL realizado na fase inicial, o foco aqui foi a construção de modelos preditivos para antecipar a evasão de clientes.

## 🎯 Objetivo da Fase 2
O objetivo principal foi utilizar técnicas de **Machine Learning** para responder: *Quem são os clientes com maior risco de deixar a empresa?* Com uma acurácia de **81%**, o modelo desenvolvido permite que a Telecom X tome decisões proativas para reter seus usuários.

## 🛠️ Tecnologias e Bibliotecas
* **Python 3.x**
* **Pandas & NumPy**: Processamento de dados e engenharia de variáveis.
* **Scikit-Learn**: Criação, treino e avaliação do modelo de Machine Learning.
* **Matplotlib & Seaborn**: Visualização de correlações e matriz de confusão.

## 🧠 Desenvolvimento Técnico
Nesta etapa, o projeto seguiu o seguinte fluxo:

1. **Feature Engineering**: Transformação de variáveis categóricas (strings) em numéricas (Encoding) para processamento algorítmico.
2. **Análise de Correlação**: Identificação de que o contrato "Mês a Mês" e o serviço de "Fibra Ótica" são os maiores indicadores de Churn.
3. **Modelagem**: Implementação do algoritmo de **Regressão Logística**.
4. **Validação**: Divisão do dataset em 80% para treino e 20% para teste, garantindo a neutralidade da avaliação.



## 📊 Resultados e Performance
O modelo final apresentou resultados sólidos:
* **Acurácia Geral**: 81.35%
* **Matriz de Confusão**: O modelo demonstrou alta precisão em identificar clientes fidelizados e uma boa taxa de recuperação para identificar perfis de evasão.



## 💡 Insights de Negócio
* **Fidelização**: Clientes com contratos de 1 ou 2 anos têm risco de churn drasticamente menor.
* **Alerta de Risco**: Clientes que utilizam faturas sem papel e métodos de pagamento eletrônico tendem a ter maior rotatividade, exigindo atenção especial do time de retenção.

## ✒️ Autor
* **Marcelo** - [Meu Perfil no LinkedIn](https://www.linkedin.com/in/marcelodasilvacamilo/)
* Formação: Cientista de Dados - Oracle One (Alura)
