# Machine Learning: classificacao de doença renal crônica (DRC)

Bem-vindo ao repositório do projeto que usa machine learning para prever complicações renais com alta precisão! Aqui, exploramos como Random Forest e SVM podem ajudar em diagnósticos médicos, evitando falsos negativos.

##  📌 Resumo do Projeto
✅ Objetivo: Desenvolver um modelo confiável para identificar pacientes com risco de complicações renais.

✅ Dados: Características fisiológicas coletadas de um hospitala ao longo de 2 meses.

✅ Resultados: Recall > 96% (quase nenhum caso positivo escapou!).


## ⚙️ Como Funciona?

Práticas de machine learning foram utilizadas para preparar os dados e aplicar algoritmos de classficação para predição de DRC.

### 🛠️🔨Pré-processamento:

- Encoding dos dados categóricos
- Normalização dos dados
- Imputação de valores faltantes
- Separação em treino e teste

### 🤖 Algoritmos

SVM: Baseado em distâncias
Random Forest

### Validação:

- StratifiedKFold para métricas confiáveis.
- Grid Search para otimizar hiperparâmetros.
- Matriz de confusão
- Métricas: recall, f1-score, acurácia


### 📈 Resultados e Discussão

asas

### 🔻Limitações:

O dataset poderia ser maior para melhor generalização.

## 🚀 Melhorias Futuras

Aplicar mais técnicas de pré processamento como feature selection.

Conseguir mais dados para o algoritmo


## 📚 Referências
Scikit-learn: [Documentação Oficial](scikit-learn.org/stable/modules/svm.html) 📄

Artigo [_Classification of chronic kidney disease based on machine
learning techniques_](https://www.academia.edu/download/107245053/32116_68219_1_PB.pdf)

Dataset: [Chronic Kidney Disease dataset](https://www.kaggle.com/datasets/mansoordaku/ckdisease)

Para mais detalhes veja o [_notebook_](https://github.com/intel-comp-saude-ufes/2025-1-P1-classificacao-de-doenca-renal-cronica/blob/main/kidney_disease.ipynb) ou o [INSERIR LINK DO ARTIGO]

---

## 👥 Autores & Contato

| Nome  	|  github 	|  email 	|  
|---	|---	|---	|
| Alex Oliveira  	|   🐙🐱 @alekswheeler	|   aleks.vix@outlook.com	|  
| Icaro Madalena  	|   🐙🐱 @bvl0	|   	|   .com

Feito com ❤️ e Python
