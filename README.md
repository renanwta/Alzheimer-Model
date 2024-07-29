# Alzheimer-Model

# Sobre


# Ferramentas
## Python
- Tratamento dos dados: Pandas
- Biblioteca de Machine Learning: Sklearn
- Biblioteca de seleção de Features: SelectKBest e F_classifier 
- Bibliotecas de pré processamentos: Imblearn e Sklearn
- Gráficos: Seaborn e Matplotlib

## Base de dados utilizado
  A base de dados é pública e foi retirada no site da UCI Machine Learning Repository:

Cortez,Paulo, Cerdeira,A., Almeida,F., Matos,T., and Reis,J.. (2009). Wine Quality. UCI Machine Learning Repository. https://doi.org/10.24432/C56S3T.

# Resultados
Após todos os tramentos e pré processamento dos dados, foi refeita os modelos de de SVC e Logistic Regression, assim, para poder validar e veriicar qual dos modelos a serem utilizados, foi calculado o a curva ROC e a pontuação AUC.
<div align="center">
<img src="https://github.com/renanwta/Red-Wine/assets/161327900/caf9aec9-482b-4fc0-9037-c08f5ed6d716" width="500px" />
</div>
Para a curva ROC do modelo de SVC temos que a pontuação AUC foi de 85%

<div align="center">
<img src="https://github.com/renanwta/Red-Wine/assets/161327900/c22ff154-8ec6-4518-884e-5093a1bb52c3" width="500px" />
</div>
Já para a curva ROC do modelo de SVC temos que a pontuação AUC foi de 81%


Assim dizemos que o melhor modelo a ser utilziado será o modelo de SVC para prever as classes da qualidade do vinho


# Step by Step
1. Importação dos dados
2. Conhecendo os dados

   2.1 Observando os Outliers
   
   2.2 Tratando os Outliers
   
   2.3 Histograma após o tratamento

3. Selecionando as features

   3.1 Encontrando as Colunas

4. Criação dos modelo Suport Vetorial Classification - SVC
   
   4.1 Cálculo do base line
   
5. Criação dos modelo Logistic Regression
   
   5.1 Cálculo do base line

6. Primeira Conclusão
7. Rebalanceamento dos dados da variável dependente
8. Novo Modelo de SVC
   
 8.1 Cálculo da Curva ROC e pontuação AUC
 
9. Novo Modelo de Logistic Regression

    9.1 Cálculo da Curva ROC e pontuação AUC

10. Segunda Conclusão
11. Cálculo Pontuais
