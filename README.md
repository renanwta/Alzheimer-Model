# Alzheimer-Model

# Sobre
O objetivo deste projeto foi criar um modelo preditivo capaz de detectar a possível presença dessa doença utilizando dados como características demográficas, estilo de vida, histórico médico, avaliação funcional e cognitiva, além dos sintomas do paciente. Isso permite que, mesmo na ausência dos sintomas mais leves, o modelo possa identificar a probabilidade de o paciente desenvolver a doença antes do aparecimento dos sintomas. 

# Ferramentas
## Python
- Tratamento dos dados: Pandas
- Biblioteca de Machine Learning: Sklearn
- Ferramentas de seleção de Features: Chi² e F_classifier 
- Ferramentas de pré processamentos: SMOTE e Normalize
- Gráficos: Seaborn e Matplotlib
- Modelos de ML: Logistic Regression, SupportVetorialClassifier (SVC) e RandomForestClassifier

 
## Base de dados utilizado
Title: Rapid Alzheimer's Disease Diagnosis Using Advanced Artificial Intelligence Algorithms

DOI: 10.38124/ijisrt/IJISRT24JUN1915

# Resultados

A Seleção do modelo foi feito baseado nos resultado das pontuação AUC, curva ROC e com os valores do Cross-Validation entre cada um dos modelos. Assim, análisando os resultados, foi selecionado o modelos de RCF já que possui a curva mais acentuada, o valor de AUC maior e com a média de accurácia maior em relação aos outros modelos.



<div align="center">
<img src="https://github.com/user-attachments/assets/03bbd24b-e8b0-4716-a3d7-782625e88dc3" width="500px" />
</div>



<div align="center">
<img src="https://github.com/user-attachments/assets/5a5af5fe-3517-421f-86dd-f69c5707f068" width="200px" />
</div>


# Step by Step
1. Importação dos dados
2. Conhecendo os dados
3. Tratamento de dados

   3.1 Observando os Outliers
   
   3.2 Matriz de correlação
   
4. Seleção de features
   4.1 Seleção de Feeatures com f_classif

   4.2 Seleção de Features com Chi²

   4.3 Juntado as features

5. Observando o balanço do Target
   
   5.1 Balanceando o Dataset
   
6. Normalização dos dados
   
7. Criando Modelos de Machine Learning
   
   7.1 Logistic Regression
   
        7.1.1 Cross Validation Logistic Regression
   
        7.1.2 Cruva ROC e AUC
   
   7.2 SVC
   
        7.2.1 Cross Validation SVC
   
        7.2.2 Cruva ROC e AUC

   7.3 RandomForestClassifier
   
        7.2.1 Cross Validation RandomForestClassifier
   
        7.2.2 Cruva ROC e AUC
   
   7.4 Escolhendo o modelo

8. Analisando os Hiperparamentros
   8.1 Validação do modelo com Nested Score Validation

9. Resultados e Análises
