# Gerador de contratos no Word

Script em Python que lê uma planilha de fornecedores e gera um contrato de prestação de serviço em Word (`.docx`) para cada linha.

## Como funciona

1. Lê o arquivo `fornecedores.xlsx` (nome, endereço, cidade, estado, CEP, telefone, e-mail e setor)
2. Preenche o texto do contrato com os dados de cada fornecedor
3. Salva um arquivo por fornecedor na pasta `contratos/`

Os dados da planilha são fictícios. A pasta `contratos/` já traz os arquivos gerados como exemplo.

## Como rodar

```bash
pip install -r requirements.txt
python app.py
```
