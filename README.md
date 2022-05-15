#  📈 Regressão Linear simples

Este projeto tem como intuito utilizar o **Python** para realizar um processo de predição dos valores a serem cobrados pela diária da locação de determinado imóvel, o desafio foi proposto no **Bootcamp DiversiData Tech Pan** realizado pela **IGTI**em parceria com o **Banco Pan**.</p>


#### 🔎  Case:
Uma empresa do ramo imobiliário quer criar um modelo preditivo que utiliza os **dados de valor do custo da diária e quantidade de pessoas**. Ela possui uma base de dados histórica que contém a quantidade pessoas e o valor cobrado no custo da diária.

Diante disso, a empresa contratou uma consultoria de tecnologia para auxiliar no processo de predição. Os analistas perceberam que a melhor abordagem para esse problema é criar um algoritmo de Machine Learning de regressão linear para predizer o **valor da diária do imóvel baseado na quantidade de pessoas que realizaram a diária**.


## O que é Regressão Linear? 

A Regressão é uma técnica que tem por objetivo predizer o valor de uma variável dependente (Y) quando temos um conjunto de valores que são as variáveis independentes (X).

*Fórmula*
``` 
y=β0+β1∗x+ϵ

```     
Sendo:
* y o valor estimado da venda
* β0 é um valor de constante para que o resultante ponto toque o eixo y (ou seja, onde x vale 0 portanto ponto (0,y) ).
* β1 é a inclinação da reta, ou seja, o coeficiente angular da reta.
* ϵ é a parcela de erro


### insights


O gráfico abaixo representa os valores cobrados no custo da diária da empresa x. é possível notar que não existe um padrão para cobranças uma vez que a relação entre pessoa e custo nem sempre é **proporcional**, existem casos onde um **número menor de pessoas paga mais caro** que **outro grupo com mais pessoas**. 

![Screenshot](./img/sem%20analise.png)


Após realizarmos a previsão é encontrado uma proporcionalidade entre os valores cobrados e o número de pessoas, ao analisarmos podemos recomendar uma adequação nos valores cobrados, possibilitando uma cobrança mais justa para os cliente.

![Screenshot](./img/com%20analise.png)