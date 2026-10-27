# FraudRadar

Projeto acadêmico de monitoramento de transações suspeitas
utilizando Machine Learning e análise histórica de contas.

## Tecnologias

- Python
- Pandas e NumPy
- Scikit-learn
- Jupyter Notebook

## Dataset

O projeto utiliza o SAML-D, um dataset sintético de transações
para pesquisa em monitoramento de lavagem de dinheiro.

O dataset não é incluído neste repositório. Consulte sua fonte
original e licença antes de utilizá-lo.

Coloque o arquivo em data/raw/SAML-D.csv.

## Instalação

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt