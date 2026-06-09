# Respostas do Projeto - Comparação Deep Learning e Machine Learning 

## QUAL FOI O MODELO TRADICIONAL ESCOLHIDO?

O modelo tradicional escolhido foi o Random Forest. A escolha foi feita porque esse algoritmo é bastante eficiente em problemas de classificação e costuma apresentar bons resultados em bases de dados estruturadas, como a utilizada neste trabalho.

---

## QUAL FOI A ESTRUTURA DA REDE NEURAL?

A rede neural foi composta por duas camadas principais responsáveis por aprender os padrões das transações e uma camada final que realizou a classificação entre transações fraudulentas e não fraudulentas. Também foi utilizado um mecanismo para evitar que o modelo decorasse os dados de treinamento, melhorando sua capacidade de generalização.

---

## QUAL MODELO TEVE A MELHOR RECALL PARA FRAUDE?

O Random Forest apresentou um desempenho um pouco melhor na identificação de fraudes. Ele conseguiu detectar mais casos fraudulentos do que a rede neural, mostrando maior eficiência nessa tarefa.

---

## QUAL MODELO TEVE MELHOR PRECISION?

O Random Forest também apresentou os melhores resultados nesse aspecto. Isso mostra que ele foi mais confiável ao indicar quais transações eram realmente fraudulentas, cometendo menos erros de classificação do que a rede neural.

---

## A REDE NEURAL APRESENTOU SINAIS DE OVERFITTING?

A rede neural não apresentou sinais relevantes de overfitting. Durante o treinamento, os resultados obtidos nos dados de treino e validação permaneceram muito próximos, indicando que o modelo conseguiu aprender os padrões dos dados de forma equilibrada.

---

## DEEP LEARNING FOI REALMENTE NECESSÁRIO NESSE PROBLEMA?

Com base nos resultados obtidos, o uso de Deep Learning não trouxe vantagens significativas para este problema. Embora a rede neural tenha apresentado um bom desempenho, o Random Forest obteve resultados melhores na detecção de fraudes. Dessa forma, um modelo tradicional já foi suficiente para atender aos objetivos da atividade de maneira eficiente.

---

## QUAL MODELO VOCÊ ESCOLHERIA PARA A EMPRESA? POR QUÊ?

Eu escolheria o Random Forest para ser utilizado pela empresa. Durante os testes, ele apresentou os melhores resultados na identificação de fraudes e se mostrou mais eficiente do que a rede neural. Além disso, é um modelo mais simples de implementar e utilizar. Como o objetivo principal é detectar fraudes com a maior precisão possível, o Random Forest seria a opção mais adequada para esse cenário.
