# Limpeza_Vendas

Este projeto realiza a limpeza e análise de dados de vendas, com foco em corrigir inconsistências, tratar valores ausentes e preparar os dados para análises mais aprofundadas.

## Estrutura do Projeto

- **`vendas_certo.ipynb`**: Notebook principal que contém o processo de limpeza e transformação dos dados.
- **`vendas_certo.csv`**: Arquivo CSV com os dados de vendas após a limpeza.
- **`regras_associação.ipynb`**: Notebook que aplica regras de associação para identificar padrões de compra.
- **`.gitattributes`**: Configurações de atributos do Git.
- **`README.md`**: Documentação do projeto.

## Funcionalidades

1. **Limpeza de Dados**:
   - Remoção de caracteres indesejados em colunas como `produto` e `valor`.
   - Padronização de nomes de produtos.
   - Preenchimento de valores ausentes em colunas críticas como `frete` e `data`.
   - Detecção e correção de outliers.

2. **Transformações**:
   - Formatação de colunas numéricas para duas casas decimais.
   - Substituição de valores inválidos, como CEPs incorretos, pela mediana da cidade correspondente.

3. **Análise de Dados**:
   - Identificação de registros duplicados.
   - Geração de estatísticas descritivas com o método `describe`.
   - Aplicação de regras de associação para identificar padrões de compra.

## Como Executar

1. Certifique-se de ter o Python 3 instalado.
2. Instale as dependências necessárias:
   ```bash
   pip install pandas numpy matplotlib