# Relatório de Atividades Práticas – Data Science Algorithms

Este repositório contém o relatório das atividades práticas avaliativas do curso de **Graduação em Ciência de Dados** da **Universidade Cruzeiro do Sul**, referentes à disciplina **Data Science Algorithms**.

---

## Análise 1 – Clustering e Regras de Associação

**Objetivo:**  
Analisar as características dos clusters gerados e relacioná-los com as regras de associação obtidas pelo algoritmo Apriori.

**Arquivo utilizado:** `NumECateg.csv`  

**Descrição do experimento:**  
- O conjunto de dados foi analisado a partir da geração de clusters utilizando o método de clusterização K-Means.
- Paralelamente, com o algoritmo Apriori para identificar padrões e associações entre os atributos.  
- O relatório descreve a relação entre as regras encontradas e os grupos de dados, interpretando os padrões e as tendências observadas.  

**Resultados:**  
- Foram identificadas regras de associação relevantes que apontam comportamentos específicos nos clusters.  
- O relatório detalha cada cluster com suas características e associa as regras que mais se aplicam a cada grupo, permitindo entender como os atributos interagem dentro da base de dados.
---

## Análise 2 – Análise do Gráfico de Erro RMS com K-Means

**Objetivo:**  
Determinar o melhor número de clusters para a base **IrisDataSet** utilizando o erro RMS.

**Arquivo utilizado:** `iris.csv`  

**Descrição do experimento:**  
- O atributo referente às variedades originais das flores (Setosa, Versicolor e Virginica) foi removido para que o K-Means criasse clusters sem referência às classes verdadeiras.  
- O algoritmo K-Means foi executado no Weka testando diferentes números de clusters (*k*).  
- O desempenho do modelo foi avaliado utilizando o **erro RMS (Root Mean Square)**, onde valores menores indicam clusters mais bem ajustados.

**Conclusão:**  
O gráfico de RMS mostrou que o erro diminui rapidamente até **3 clusters**, estabilizando-se a partir desse ponto. Isso indica que **3 clusters são suficientes para representar a estrutura natural da base Iris**, mesmo sem o atributo de classe original.

---

**Observação:**  
Este repositório é destinado a fins acadêmicos, como atividade prática avaliativa da disciplina **Data Science Algorithms**.
