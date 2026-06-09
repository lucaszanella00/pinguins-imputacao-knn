# 🐧 Imputação de Dados com KNN - Dataset Palmer Penguins

Projeto acadêmico desenvolvido na disciplina de **Mineração e Visualização de Dados**
(1º semestre - Ciência de Dados e IA)

---

## Descrição

O dataset Palmer Penguins foi utilizado como base para um desafio de imputação de dados faltantes.
30% das células foram removidas aleatoriamente, simulando cenários reais de dados incompletos.

---

## Tecnologias

- **Python** (pandas, numpy, scikit-learn, seaborn)
- **Power BI** (visualização e comparativo Antes x Depois)
- **Google Colab**

---

## Metodologia

- Remoção aleatória de 30% das células (seed=42 para replicabilidade)
- Encoding das variáveis categóricas com `OrdinalEncoder`
- Imputação com `KNNImputer`
- Exportação dos dados para visualização no Power BI

---

## Resultados

| | Antes | Depois |
|---|---|---|
| Registros completos | 32 (9,3%) | 344 (100%) |
| Registros com missing | 312 | 0 |

A estrutura estatística do dataset foi preservada após a imputação — médias, medianas e desvios padrão permaneceram praticamente inalterados.

---

## Arquivos

- `MD_trabalho2.ipynb` — Notebook com todo o pipeline de imputação
- `penguins_MDV_final.pbix` — Dashboard Power BI

---

## Autor

Lucas Zanella — Analista de BI & estudante de Ciência de Dados
[GitHub](https://github.com/lucaszanella00)
