# 🚦 Previsão de Fluxo de Tráfego Rodoviário no Porto

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Grade](https://img.shields.io/badge/Nota_Final-18.2%2F20-brightgreen)
![Kaggle](https://img.shields.io/badge/Kaggle_Rank-4º_Lugar-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)

Este projeto foi desenvolvido no âmbito da Unidade Curricular de **Dados e Aprendizagem Automática** (2025/2026) da Universidade do Minho. O objetivo foi desenvolver modelos de Machine Learning para prever o fluxo de tráfego no Porto, seguindo a metodologia **CRISP-DM**.

---

## 🏆 Conquistas
* **Classificação:** 18,2 valores.
* **Competição Kaggle:** 4º Lugar (entre 57 equipas).
* **Competição:** [Competição ML @DAA - Edição 2025/2026](LINK_DA_COMPETICAO_AQUI)

## 📊 Resumo dos Resultados
O nosso modelo final destacou-se pela consistência entre a validação local e o teste público/privado:

| Métrica | Score |
| :--- | :--- |
| **Validação Local** | 82.0% |
| **Kaggle Public Score** | 83.5% |
| **Kaggle Private Score** | 81.3% |

> 📄 **Relatório Completo:** [Ver PDF do Relatório](./report.pdf)
> *(Recomendamos a leitura para detalhes sobre a análise exploratória e decisões de modelação)*

---

## 👥 Autores (Grupo 34)
* **Luís Silva** (PG60390)
* **Guilherme Pinto** (PG60225)
* **Pedro Reis** (PG59908)
* **João Azevedo** (PG61693)

---

## 📂 Estrutura do Repositório
* `report.pdf`: Relatório técnico detalhado.
* `code.ipynb`: Notebook com o modelo final e pipeline de submissão.
* `dev/`: Histórico de desenvolvimento (EDA, testes com SVM, XGBoost, etc.).
* `datasets/`: Dados utilizados no treino e teste.
* `images/`: Gráficos gerados durante a análise.

---

## 🚀 Instalação e Configuração

Para reproduzir os resultados apresentados no relatório, recomenda-se a criação de um ambiente virtual através do ficheiro `env.yml` fornecido.

### Pré-requisitos
* **Git** instalado.
* **Anaconda** ou **Miniconda** instalado.

### Passos de Instalação

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/GuilhermeLobo225/DAA.git](https://github.com/GuilhermeLobo225/DAA.git)
   cd DAA
   ```
2. **Criar o ambiente virtual:**
    ```bash
   conda env create -f env.yml
   ```
3. **Ativar o ambiente:**
    ```bash
    conda activate daa-env
    ```
4. **Gerar Resultados:** Execute o notebook code.ipynb. O ficheiro submission.csv será gerado automaticamente.

---
## 📊 Resumo dos Resultados
- Validação Local: 82%
- Kaggle Public Score (30%): 83,5%
- Kaggle Private Score (70%): 81,3%

---

## 📜 Licença
Este trabalho é de cariz estritamente académico. Universidade do Minho, Escola de Engenharia, Departamento de Informática.
