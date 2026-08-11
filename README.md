# Bryan Smith

Data Scientist & Data Engineer at Peregrine Capital, based in South Africa. I build data platforms and run quantitative research, then write up the "why," not just the "what": most of the repos below exist to make a specific idea (a factor model, a backprop derivation, a lakehouse architecture) checkable rather than just asserted.

- 🌐 [bryansmith.co.za](https://bryansmith.co.za)
- 💼 [linkedin.com/in/bryansmithza](https://www.linkedin.com/in/bryansmithza/)

## Projects

| Project | What it is |
|---|---|
| [**local-data-platform**](https://github.com/bryanmehsmith/local-data-platform) | A local/on-prem lakehouse for batch + streaming ETL (Dagster, Redpanda, MinIO, Iceberg via Nessie, Trino/DuckDB, dbt), plus a local AI chat layer with RAG and text-to-SQL over the lakehouse (Ollama, Qdrant, Open WebUI). Scales from a single machine to a small cluster without changing tools. |
| [**factor-regression-lab**](https://github.com/bryanmehsmith/factor-regression-lab) | An interactive Streamlit app for factor regression on US equities (CAPM → FF3 → FF5 → FF5+Momentum): is an asset's outperformance skill, or just factor exposure it wasn't naming? Compares classical, White, and Newey-West standard errors side by side, with VIF and rolling-beta stability diagnostics. |
| [**nn-foundations-lab**](https://github.com/bryanmehsmith/nn-foundations-lab) | A neural-network library built from scratch in NumPy (tensors, layers, manual backprop, SGD/Adam/AdamW, gradient checking), reproduced line-for-line in PyTorch to verify it. Every derivation is checked two ways: numerically (gradcheck) and against real PyTorch training (parity). |
| [**basic-jse-momentum-factor**](https://github.com/bryanmehsmith/basic-jse-momentum-factor) | 12-1 momentum factor research and backtesting on the JSE using `yfinance`: signal construction, quantile portfolios, and performance/turnover reporting. |
| [**demo-site**](https://github.com/bryanmehsmith/demo-site) | The hosting platform behind my POC demos: one Azure Container App, one Caddy reverse proxy, static demos served directly and Streamlit demos pulled in as submodules, each auto-published on push. |
| [**personal-website**](https://github.com/bryanmehsmith/personal-website) | This site: React + React Router, deployed as an Azure Static Web App, resume compiled from LaTeX in CI. |

## Stack

`Python` `SQL` `Azure` `Microsoft Fabric` `Docker` `React`

Data/ML: `Dagster` `dbt` `Trino` `Apache Iceberg` `pandas` `NumPy` `PyTorch` `Streamlit`
