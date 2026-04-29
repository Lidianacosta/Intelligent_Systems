# Sistemas Inteligentes (Intelligent Systems)

Este repositório centraliza as atividades e projetos acadêmicos desenvolvidos para a disciplina de **Sistemas Inteligentes** (PAM0466) na **UFERSA**. O objetivo é a implementação, análise e documentação de algoritmos de aprendizado de máquina aplicados a diferentes problemas reais.

---

## 🎓 Contexto Acadêmico

- **Instituição:** UFERSA - Universidade Federal Rural do Semi-Árido
- **Disciplina:** Sistemas Inteligentes
- **Docente:** Pedro Thiago Valério de Souza
- **Semestre:** 2026.1

## 👥 Autores

- **Lidiana Costa de Souza** - Matrícula: 2026010134
- **Antonio Welles Queiroz De Paiva** - Matrícula: 2021011812

---

## 📂 Projetos e Atividades Implementadas

Abaixo estão listados os módulos desenvolvidos até o momento:

### 1. Regressão Linear ([`/linearRegression`](/linearRegression/atividade_I.ipynb))

- **Foco:** Predição de valores contínuos.
- **Atividade I:** Análise de correlação entre variáveis físico-químicas e métricas de erro (MAE, MSE, RMSE).

### 2. Regressão Logística ([`/LogisticRegression`](./LogisticRegression/Projeto2_regressao_logistica.ipynb))

- **Foco:** Classificação binária.
- **Atividade II:** Diagnóstico assistido utilizando o dataset _Heart Disease Cleveland_. Inclui pré-processamento, binarização de alvos e análise de Curva ROC/AUC.

### 3. K-Nearest Neighbors - KNN ([`/knn`](./knn/atividade_III.ipynb))

- **Foco:** Classificação baseada em proximidade.
- **Atividade III:** Classificação da qualidade de vinhos (dataset _Wine Quality_). Implementa normalização Min-Max, busca pelo $k$ ideal via validação cruzada e análise detalhada da Matriz de Confusão.

---

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python 3.12+
- **Ambiente:** Jupyter Notebook
- **Principais Bibliotecas:**
  - `Scikit-learn` (Modelos e Métricas)
  - `Pandas` & `NumPy` (Manipulação de dados)
  - `Matplotlib` & `Seaborn` (Visualização)
- **Gerenciador de Dependências:** [uv](https://github.com/astral-sh/uv)

---

## 🚀 Como Executar

Este projeto utiliza o `uv` para garantir a reprodutibilidade do ambiente.

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/Lidianacosta/Intelligent_Systems.git
   cd Intelligent_Systems
   ```

2. **Configure o ambiente virtual:**

   ```bash
   uv venv
   source .venv/bin/activate  # Linux/macOS
   # No Windows: .venv\Scripts\activate
   ```

3. **Instale as dependências:**

   ```bash
   uv sync
   ```

4. **Inicie o Jupyter:**
   ```bash
   jupyter notebook
   ```

---
