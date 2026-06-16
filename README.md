<div align="center">

# 📓 `gustavo_varadi.ipynb`

### *Uma análise exploratória de um Analista / Cientista de Dados*

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=F37626&center=true&vCenter=true&width=720&lines=Kernel%3A+Python+3+%C2%B7+pronto+para+rodar;Analista+de+Dados+%E2%86%92+Cientista+de+Dados;Pipelines+ELT+%C2%B7+ML+%C2%B7+BI+%C2%B7+Storytelling+com+dados" alt="Typing SVG" />
</a>

![Kernel](https://img.shields.io/badge/kernel-Python%203-3776AB?style=flat-square&logo=python&logoColor=white)
![Run](https://img.shields.io/badge/run-all%20cells%20%E2%96%B6-F37626?style=flat-square)

</div>

---

```python
In [1]: import gustavo as eu
        import pandas as pd

        print(eu.__doc__)
```
```text
Out[1]: Analista de Dados @ naPorta, em transição para Cientista de Dados.
        Construo pipelines ELT, Data Warehouses e modelos de ML de ponta a ponta —
        e traduzo o resultado para quem decide.
```

---

### 🔎 `In [2]` — Inspeção inicial: quem é esse registro?

```python
In [2]: eu.head()
```

| campo | valor |
|---|---|
| **nome** | Gustavo Varadi |
| **cargo** | Analista de Dados @ naPorta |
| **transição** | Analista → Cientista de Dados |
| **localização** | São Paulo, Brasil 🇧🇷 |
| **idiomas** | Português (nativo) · English (intermediate) |
| **diferencial** | levo o dado do caos cru à decisão executiva |

---

### 📊 `In [3]` — Estatística descritiva das skills

```python
In [3]: eu.skills.describe()
```

<div align="center">

**Linguagens & Análise**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-avan%C3%A7ado-025E8C?style=flat-square&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Engenharia de Dados**

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![ELT/ETL](https://img.shields.io/badge/ELT%2FETL-4B5563?style=flat-square)

**Viz / BI & Cloud**

![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

### 🤖 `In [4]` — Treinando o modelo de carreira

```python
In [4]: from sklearn.pipeline import Pipeline

        carreira = Pipeline([
            ("coleta",      WebScraping(tool="Selenium")),
            ("ingestao",    ELT(orchestrator="Airflow", transform="dbt")),
            ("modelagem",   DataWarehouse(cloud="BigQuery", layers="Medalhão")),
            ("ml",          Model("scikit-learn")),
            ("entrega",     Dashboard("Looker Studio")),
        ])
        carreira.fit(dados_brutos)
```
```text
Out[4]: Pipeline treinado ✅  →  do dado cru ao insight de negócio.
```

**🏛️ Projeto em destaque — Data Warehouse da naPorta** *(arquitetado solo)*
Arquitetura Medalhão no BigQuery integrando múltiplas fontes (clientes, Shopee, Amazon), orquestração ELT com **dbt + Airflow**, modelos de **ML** para previsão operacional e dashboards no **Looker Studio** usados por sócios em reuniões com investidores.

---

### 🎯 `In [5]` — Avaliação: métricas de impacto

```python
In [5]: eu.impacto.evaluate()
```

<div align="center">

| ⏱️ tempo manual | 🎯 acurácia dos relatórios | 📉 tempo de análise | 🏗️ data warehouse |
|:---:|:---:|:---:|:---:|
| **−96 h/mês** | **+25 %** | **−16,5 %** | **do zero** |

</div>

---

### 📈 `In [6]` — Visualizando a atividade

```python
In [6]: eu.github.plot()
```

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=gvaradi&show_icons=true&hide_border=true&theme=vue-dark&count_private=true" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gvaradi&layout=compact&hide_border=true&theme=vue-dark&langs_count=8" alt="top langs" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=gvaradi&hide_border=true&theme=vue-dark" alt="streak" />

</div>

---

### 🤝 `In [7]` — Contato

```python
In [7]: eu.connect()
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/SEU-USUARIO)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:SEU-EMAIL@exemplo.com)

</div>

```text
Out[7]: 🚀 Vamos transformar dados em decisão? Me chama.
```
