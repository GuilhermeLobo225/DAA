# Previsão de Fluxo de Tráfego Rodoviário no Porto 🚦

Este projeto foi desenvolvido no âmbito da Unidade Curricular de **Dados e Aprendizagem Automática** (2025/2026) da Universidade do Minho. O objetivo principal é o desenvolvimento de modelos de Machine Learning capazes de prever o fluxo de tráfego rodoviário na cidade do Porto, seguindo a metodologia **CRISP-DM**.

🏆 **4º Lugar na Competição Kaggle** (Entre 57 equipas)
🔗 **Competição:** [Competição ML @DAA - Edição 2025/2026](https://www.kaggle.com/competitions/DAA-TG)

📄 **Relatório Completo:** [Ver PDF do Relatório](./report.pdf)
*(Recomendamos a leitura do relatório para detalhes profundos sobre a análise exploratória, decisões de modelação e discussão dos resultados)*

## 👥 Autores (Grupo 34)

* **Luís Silva** (PG60390)
* **Guilherme Pinto** (PG60225)
* **Pedro Reis** (PG59908)
* **João Azevedo** (PG61693)

---

## 📂 Estrutura do Repositório

* `report.pdf`: Relatório técnico detalhado do projeto.
* `code.ipynb`: Notebook com o **modelo final** e o pipeline de geração da submissão.
* `dev/`: Pasta contendo todo o processo de desenvolvimento, incluindo a **análise exploratória de dados (EDA)** e os testes com os vários modelos (Decision Tree, SVM, XGBoost, etc.).
* `datasets/`: Pasta contendo os ficheiros de dados.
* `env.yml`: Ficheiro de configuração do ambiente Conda com todas as dependências necessárias.
* `submission/`: Pasta onde são gerados os ficheiros de submissão para o Kaggle.
* `images/`: Imagens e gráficos gerados durante a análise.

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