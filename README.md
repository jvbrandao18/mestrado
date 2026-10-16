# 🎓 Mestrado | PUCPR

Repositório dedicado à organização e documentação dos estudos, atividades e projetos desenvolvidos durante meu mestrado na **Pontifícia Universidade Católica do Paraná (PUCPR)**.

O objetivo é consolidar conhecimentos teóricos e práticos, explorar metodologias computacionais e aplicar técnicas de análise de dados, automação, inteligência artificial e mineração de processos na resolução de problemas.

## 📚 Áreas de Estudo

- Inteligência Artificial e Machine Learning
- Mineração de Processos (Process Mining)
- Ciência e Análise de Dados
- Automação e Otimização de Processos
- Desenvolvimento de Soluções com Python
- Modelagem, Avaliação e Comparação de Algoritmos

## 🏫 Disciplina — PDMPI

**Pipeline de Desenvolvimento de Mineração de Processos na Indústria**

A disciplina aborda conceitos, técnicas e ferramentas relacionados à análise de processos organizacionais, com foco na aplicação de métodos computacionais para identificação de padrões, análise de desempenho e apoio à tomada de decisão.

### Conteúdo desenvolvido

| Aula | Tema | Atividades |
|------|------|------------|
| 05 | Machine Learning | Classificação, regressão, análise exploratória, validação cruzada e comparação de algoritmos |

*O repositório será atualizado conforme o desenvolvimento das atividades acadêmicas.*

---

## 🤖 Projeto — Machine Learning aplicado ao Process Mining

### Objetivo

Aplicar algoritmos de aprendizado supervisionado a um conjunto de dados de eventos de processos organizacionais, buscando identificar padrões e prever os resultados de projetos.

### Dataset

O conjunto de dados utilizado contém:

- **23.388 eventos**
- **1.200 processos distintos**
- **22 atributos originais**
- **3 classes de resultado**

As classes analisadas foram:

- `Completed On Time`
- `Completed Late`
- `Cancelled`

### Metodologia

O desenvolvimento seguiu cinco etapas:

1. **Exploração dos dados:** identificação de atributos, tipos, distribuições e valores ausentes.
2. **Análise univariada:** estatísticas descritivas, histogramas e identificação de outliers.
3. **Análise multivariada:** correlações e investigação de relações entre características dos processos.
4. **Engenharia de atributos:** seleção de variáveis preditoras e definição da variável-alvo.
5. **Modelagem e avaliação:** treinamento de algoritmos e comparação utilizando validação cruzada.

### Algoritmos avaliados

- K-Nearest Neighbors (KNN)
- Decision Tree
- Naive Bayes
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)

A avaliação utilizou **Stratified K-Fold Cross-Validation**, com quatro divisões, considerando acurácia e F1-score macro.

### Resultados

| Algoritmo | Acurácia média | F1 Macro |
|-----------|---------------|----------|
| SVM (RBF) | 58,50% | **0,3987** |
| KNN | 54,50% | 0,3875 |
| Naive Bayes | **58,67%** | 0,3769 |
| MLP | 51,25% | 0,3675 |
| Decision Tree | 51,00% | 0,3664 |

O **SVM com kernel RBF** apresentou o melhor F1-score macro entre os algoritmos avaliados.

Entretanto, o modelo demonstrou limitações na identificação de processos cancelados, evidenciando desafios relacionados ao desbalanceamento das classes e à capacidade preditiva dos atributos disponíveis.

Os resultados representam um experimento acadêmico e não indicam que o modelo esteja pronto para utilização operacional.

---

## 🛠️ Tecnologias e Ferramentas

**Linguagem**
- Python

**Análise e visualização**
- Pandas
- NumPy
- Matplotlib
- Seaborn

**Machine Learning**
- Scikit-learn

**Ambiente de desenvolvimento**
- Google Colab
- Jupyter Notebook
- Git e GitHub

---

## 📂 Organização do Repositório

Estrutura sugerida para organizar as próximas atividades:

```text
Mestrado-PUCPR/
│
├── README.md
│
├── disciplinas/
│   └── PDMPI/
│       └── aula-05-machine-learning/
│           ├── notebooks/
│           │   └── Aula_05_Process_Mining_Completo.ipynb
│           │
│           └── README.md
│
└── .gitignore
```

Os materiais e datasets podem ser organizados em diretórios específicos, conforme sua disponibilidade e autorização de compartilhamento.

---

## ▶️ Execução dos Projetos

Os notebooks podem ser executados utilizando o Google Colab.

### 1. Acessar o Google Colab

https://colab.research.google.com/

### 2. Abrir o notebook

Selecione:

`Arquivo → Fazer upload de notebook`

### 3. Carregar o dataset

Disponibilize o arquivo CSV correspondente à atividade no ambiente de execução.

### 4. Executar

Selecione:

`Ambiente de execução → Executar tudo`

As análises, visualizações e avaliações dos modelos serão geradas durante a execução.

---

## 🎯 Objetivos Acadêmicos

Este repositório tem como objetivos:

- Consolidar o aprendizado por meio de implementações práticas.
- Documentar metodologias e experimentos computacionais.
- Desenvolver competências em análise de dados e inteligência artificial.
- Investigar aplicações de Machine Learning em processos organizacionais.
- Manter um histórico organizado da evolução acadêmica e técnica.

---

## 📌 Considerações

Os projetos apresentados possuem finalidade acadêmica e experimental.

Os resultados dependem das características dos datasets utilizados, das configurações dos algoritmos e dos procedimentos de validação adotados.

O repositório será atualizado ao longo do desenvolvimento das disciplinas e atividades do mestrado.

---

**Pontifícia Universidade Católica do Paraná — PUCPR**
