# Plano de Voo: SEFAZ

Dashboard de estudos em Streamlit para acompanhar progresso e edital.

## Requisitos

- Python 3.10+ (testado com 3.12)

## Instalacao

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Executar

```bash
streamlit run app.py
```

## Dados do edital (CSV)

Por padrao, o app usa `syllabus.csv` (separador `|`).

## Opcional: banco de dados

Para usar banco via SQLAlchemy, edite a `connection_string` em `app.py` e ajuste a query.
Enquanto estiver com o placeholder, o app permanece lendo o CSV.

## Estrutura

- `app.py`: app principal do Streamlit
- `syllabus.csv`: dados do edital (CSV com `|`)
