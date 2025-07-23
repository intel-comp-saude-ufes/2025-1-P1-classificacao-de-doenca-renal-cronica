# Machine Learning: classificacao de doença renal crônica (DRC)

Bem-vindo ao repositório do projeto que usa machine learning para prever complicações renais com alta precisão! Aqui, exploramos como Random Forest e SVM podem ajudar em diagnósticos médicos, evitando falsos negativos.

##  📌 Resumo do Projeto
✅ Objetivo: Desenvolver um modelo confiável para identificar pacientes com risco de complicações renais.

✅ Dados: Características fisiológicas coletadas de um hospital ao longo de 2 meses.

✅ Resultados: Recall > 96% (quase nenhum caso positivo escapou!).


## ⚙️ Como Funciona?

Práticas de machine learning foram utilizadas para preparar os dados e aplicar algoritmos de classficação para predição de DRC.

### 🛠️🔨Pré-processamento:

- _Encoding_ dos dados categóricos
- Normalização dos dados
- Imputação de valores faltantes
- Separação em treino e teste

### 🤖 Algoritmos

- _Support Vector Machine_
- Random Forest

### Validação:

- _Stratified K-Fold_ para métricas confiáveis.
- Grid Search para otimizar hiperparâmetros.
- Matriz de confusão
- Métricas: _recall_, _f1-score_, acurácia

### 🔻Limitações:

A base de dados poderia ser maior para melhor generalização.

## 🚀 Melhorias Futuras

Aplicar mais técnicas de pré processamento como _feature selection_.

Conseguir mais dados para o algoritmo


## 📚 Referências
Scikit-learn: [Documentação Oficial](scikit-learn.org/stable/modules/svm.html) 📄

Artigo [_Classification of chronic kidney disease based on machine
learning techniques_](https://d1wqtxts1xzle7.cloudfront.net/107245053/32116_68219_1_PB-libre.pdf?1699501554=&response-content-disposition=inline%3B+filename%3DClassification_of_chronic_kidney_disease.pdf&Expires=1753316238&Signature=DFwI0ns0OrHPAWZ5Fx-mVa2F0pqDZ5EmDlpakIQkUHDWeTqnMYCFLHmf7flBTcjJBwmkcYLsX2ZWLEPYlNuUN38kCZGXZ4Dd88Oq-PsmD5V0l0P1xWP~iOqsMzCdPoQ-r6h7D8iQXcOWZF01OV6wJg0mwbAksjFfZ7DN6UDSAFbBILSqMdParlz-bKhisopta1FyD9hg0sMx0KnrAOL4A42p40~1qB2yJMMdt76EQbsttfhBFXXHsVcOAo0jUaFYdT60dwHrvZilIyqudIxb7cF~8hijxGrZO04wbasfsjAK1vzba7oSWbMeT5PxN9UUltXkaNNJIHJL9JrPkDr~~g__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)

Dataset: [Chronic Kidney Disease dataset](https://www.kaggle.com/datasets/mansoordaku/ckdisease)

Para mais detalhes veja o [_notebook_](https://github.com/intel-comp-saude-ufes/2025-1-P1-classificacao-de-doenca-renal-cronica/blob/main/kidney_disease.ipynb) ou o [INSERIR LINK DO ARTIGO]

---

## 👥 Autores & Contato

| Nome  	|  github 	|  email 	|  
|---	|---	|---	|
| Alex Oliveira  	|   🐙🐱 @alekswheeler	|   aleks.vix@outlook.com	|  
| Icaro Madalena  	|   🐙🐱 @bvl0			|   icaro.nascimento@edu.ufes.br |

Feito com ❤️ e Python
