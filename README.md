# Portfolio de Extracao e Preparacao de Dados

**Aluno:** Milton Rodrigues de Sousa Filho  
**Curso:** Ciencia de Dados & IA | IBMEC  
**Semestre:** 2026.1  
**Disciplina:** Extracao e Preparacao de Dados (IBM8915)

---

## Sobre Este Repositorio

Este repositorio contem os materiais praticos desenvolvidos ao longo da disciplina, organizados por aula em diretorios de `data`, `docs`, `notebooks` e `scripts`.

## Indice de Projetos

### Modulo 1: Extracao e Analise Exploratória

Foco na obtencao de dados de diferentes fontes e na compreensao inicial dos datasets.

| Lab | Atividade | Competencias Demonstradas |
| :--- | :--- | :--- |
| **Lab 01** | [Extracao de Arquivos Planos (CSV/Excel)](./notebooks/aula_02/lab_01_flat_files.ipynb) | Leitura de CSV e Excel com `pandas`, tratamento de encoding e separadores. |
| **Lab 02** | [Extracao via SQL](./notebooks/aula_03/lab_02_sql_extraction.ipynb) | Consultas relacionais e extracao de dados a partir de banco SQLite. |
| **Lab 03** | [Analise Exploratoria Inicial (EDA)](./notebooks/aula_04/lab_03_eda_basics.ipynb) | Estatistica descritiva, tipos de variaveis e visualizacao inicial. |
| **Doc** | [Slides Aula 02](./docs/aula_02/Slides_Aula_02.md) | Material introdutorio para leitura e exploracao de arquivos planos. |

### Modulo 2: Limpeza e Tratamento de Dados

Tecnicas para transformar dados brutos em dados mais consistentes e utilizaveis.

| Lab | Atividade | Competencias Demonstradas |
| :--- | :--- | :--- |
| **Lab 04** | [Visualizacao de Dados Ausentes](./notebooks/aula_06/Lab_04_missing_values_viz_iris_datasus.ipynb) | Analise de padroes de nulidade e visualizacao de dados faltantes. |
| **Lab 05** | [Imputacao de Dados](./notebooks/aula_07/lab_05_imputation.ipynb) | Estrategias de preenchimento para valores ausentes. |
| **Lab 06** | [Tratamento de Cardinalidade](./notebooks/aula_08/lab_06_cardinality.ipynb) | Agrupamento de categorias raras e reducao de cardinalidade. |
| **Lab 09** | [Datas e Series Temporais](./notebooks/aula_10/lab_09_datetime.ipynb) | Parsing de datas e criacao de atributos temporais. |
| **Lab 11** | [Deteccao de Outliers](./notebooks/aula_11/lab_11_outliers.ipynb) | Identificacao e tratamento de outliers com tecnicas estatisticas. |

### Modulo 3: Engenharia de Atributos

Criacao de variaveis e transformacoes para apoiar analise e modelagem.

| Lab | Atividade | Competencias Demonstradas |
| :--- | :--- | :--- |
| **Lab 07** | [Encoders Categoricos](./notebooks/aula_08/lab_07_encoders.ipynb) | Transformacao de variaveis categoricas para modelos. |
| **Lab 08** | [Criacao de Features](./notebooks/aula_10/lab_10_feature_engineering.ipynb) | Geracao de novas variaveis a partir de colunas existentes. |
| **Lab 09** | [Discretizacao (Binning)](./notebooks/aula_09/lab_09_binning.ipynb) | Conversao de variaveis continuas em faixas. |
| **Avancado** | [Encoders e Tecnicas Avancadas](./notebooks/aula_09/lab_07_parte_02_advanced.ipynb) | Frequency Encoding e Target Encoding para alta cardinalidade. |

### Modulo 4: Escalonamento e Selecao de Variaveis

Tecnicas para preparar atributos para modelos e reduzir dimensionalidade.

| Lab | Atividade | Competencias Demonstradas |
| :--- | :--- | :--- |
| **Lab 12** | [Scaling e SMOTE](./notebooks/aula_12/lab_12_scaling_smote.ipynb) | Padronizacao de variaveis numericas e balanceamento de classes. |
| **Lab 13** | [SelectFromModel](./notebooks/aula_12/lab_13_select_model.ipynb) | Selecao automatica de features com modelos baseados em arvore. |
| **Lab 14** | [RFE](./notebooks/aula_12/lab_14_rfe.ipynb) | Eliminacao recursiva de variaveis para reduzir o conjunto de atributos. |

### Modulo 5: Pipelines e Automacao

Organizacao do pre-processamento em esteiras reproduziveis.

| Lab | Atividade | Competencias Demonstradas |
| :--- | :--- | :--- |
| **Exemplo** | [Codigo Espaguete](./notebooks/aula_13/Exemplo_Codigo_Espaguete.ipynb) | Comparacao entre fluxo manual fragil e fluxo estruturado. |
| **Lab 15** | [Pipelines Intro](./notebooks/aula_13/lab_15_pipelines_intro.ipynb) | Uso de `Pipeline` com imputacao e escalonamento. |

### Modulo 6: Scripts e Materiais de Apoio

Arquivos auxiliares usados nas aulas praticas.

| Tipo | Arquivo | Uso |
| :--- | :--- | :--- |
| **Script** | [Gerador de Dados de Saude](./scripts/Aula%2006/gerar_dados_saude_mock.py) | Gera dados sinteticos para atividades da aula 06. |
| **Script** | [Gerador de Censo Escolar](./scripts/Aula%2007/gerar_censo_mock.py) | Gera dados sinteticos para atividades da aula 07. |
| **Doc** | [Plano de Aula 07](./docs/aula_07/plano_de_aula_07_unificado.md) | Material de referencia para limpeza e tratamento de nulos. |

---

## Materiais Finais Disponiveis

Os artefatos mais recentes atualmente presentes no repositorio sao:

- [Lab de Outliers](./notebooks/aula_11/lab_11_outliers.ipynb)
- [Scaling e SMOTE](./notebooks/aula_12/lab_12_scaling_smote.ipynb)
- [RFE](./notebooks/aula_12/lab_14_rfe.ipynb)
- [Pipelines Intro](./notebooks/aula_13/lab_15_pipelines_intro.ipynb)
- [Aula 11 em PDF](./docs/aula_11/Aula%2011_Completa_EPD.pdf)

---

## Tecnologias Utilizadas

- Python 3.10+
- Pandas / Numpy
- Scikit-Learn
- SQLAlchemy
- Matplotlib / Seaborn
