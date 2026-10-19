# TDE 03: Construção do Baseline e Avaliação de Modelos de Regressão

Este repositório contém a entrega da atividade **TDE 03** desenvolvida para a disciplina de Aprendizado de Máquina. O objetivo do projeto é construir e avaliar o **baseline** de modelos preditivos sem otimizações avançadas de hiperparâmetros, servindo como ponto de partida para futuras comparações.

---

##  Tema e Contexto do Projeto

- **Tema:** Previsão de Consumo de Energia Elétrica Residencial (kWh).
- **Tipo de Problema:** Regressão (previsão de variável numérico-contínua).
- **Algoritmos Utilizados no Baseline:**
  1. **Regressão Linear** (Modelo Linear)
  2. **Árvore de Decisão para Regressão** (`DecisionTreeRegressor` - Modelo baseado em regras/não-linear)
- **Métricas de Avaliação Utilizadas:**
  - Erro Absoluto Médio (MAE)
  - Erro Quadrático Médio (MSE)
  - Raiz do Erro Quadrático Médio (RMSE)
  - Coeficiente de Determinação ($R^2$)

---

##  Integrantes e Estrutura dos Notebooks

O projeto foi construído de forma **acumulativa (em escada)**. Cada integrante desenvolveu e aprofundou uma etapa específica do pipeline de dados, garantindo que cada notebook execute sozinho do início ao fim.

| Integrante | Arquivo Notebook | Etapa / Foco Principal |
| :--- | :--- | :--- |
| **Lia** | `notebook_lia.ipynb` | Geração do Dataset Sintético e Análise Exploratória de Dados (EDA) |
| **Ingrid** | `notebook_ingrid.ipynb` | Pré-processamento e Engenharia de Recursos (Feature Engineering) |
| **Clara** | `notebook_clara.ipynb` | Divisão dos dados (Treino/Teste) |
| **Daniel** | `notebook_daniel.ipynb` | Implementação do Baseline 1: **Regressão Linear** |
| **Michel** | `notebook_michel.ipynb` | Métricas e Avaliação da **Regressão Linear** |
| **Morya** | `notebook_morya.ipynb` | Implementação do Baseline 2: **Árvore de Decisão** |
| **Taliciane** | `notebook_taliciane.ipynb` | Métricas e Avaliação da **Árvore de Decisão** |
| **Wesley** | `notebook_wesley.ipynb` | Análise Comparativa Lado a Lado, Discussão Crítica e Conclusão |

---

##  OBSERVAÇÃO IMPORTANTE PARA A AVALIAÇÃO / PROFESSOR

>  **Nota ao Professor:**
> 
> Como a estrutura dos notebooks foi desenvolvida de forma **acumulativa**, **cada notebook engloba e executa o código de todas as etapas anteriores a ele**.
>
> Para visualizar e avaliar o **projeto completo de ponta a ponta em um único arquivo** (desde a geração e exploração dos dados até o treinamento, cálculo das métricas e discussão comparativa final), **basta abrir e executar o último arquivo:**
>
> 📄 **`notebook_wesley.ipynb`**

---

##  Requisitos e Como Executar

### Pré-requisitos
Certifique-se de ter o Python 3.x instalado juntamente com as seguintes bibliotecas:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Execução
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd seu-repositorio
   ```
3. Abra o ambiente do Jupyter:
   ```bash
   jupyter notebook
   ```
4. Execute qualquer um dos arquivos `.ipynb` individualmente. Todos os arquivos são autônomos e executam do início ao fim sem dependências de arquivos externos.
