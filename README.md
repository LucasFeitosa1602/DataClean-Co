DataClean Co - Limpeza e Tratamento de Dados

Descrição:
Projeto focado em limpeza, tratamento e preparação de dados para análise, utilizando Python e bibliotecas de dados.

--------------------------------------------------

OBJETIVO

Demonstrar um pipeline completo de Data Cleaning, abordando problemas comuns em bases de dados reais, como:

- Valores ausentes
- Dados duplicados
- Inconsistência em datas
- Padronização de informações
- Preparação para análise

--------------------------------------------------

TECNOLOGIAS UTILIZADAS

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

--------------------------------------------------

ESTRUTURA DO PROJETO

DataClean Co/

|-- datasets/
|   |-- dados_clientes.csv
|
|-- notebooks/
|   |-- EDA.ipynb
|
|-- README.txt

--------------------------------------------------

ETAPAS DO PROJETO

1. Coleta de dados
Carregamento da base de clientes para análise.

2. Análise exploratória (EDA)
- Visualização inicial dos dados
- Identificação de inconsistências

3. Tratamento de valores ausentes
- idade: preenchida com mediana
- renda_anual: preenchida com mediana
- valor_compra: preenchido com mediana por categoria

4. Remoção de duplicatas
- Exclusão de registros duplicados completos

5. Tratamento de datas
- Conversão para formato datetime
- Criação de colunas:
  - Ano
  - Mês
  - Dia da semana

--------------------------------------------------

PRINCIPAIS APRENDIZADOS

- Importância da limpeza de dados antes da análise
- Estratégias diferentes para tratamento de nulos
- Padronização de dados temporais
- Organização de pipeline de dados

--------------------------------------------------

COMO EXECUTAR O PROJETO

1. Clone o repositório:

git clone https://github.com/seu-usuario/dataclean-co.git

2. Instale as dependências:

pip install pandas numpy matplotlib seaborn

3. Execute o notebook:

jupyter notebook

--------------------------------------------------

PRÓXIMOS PASSOS (MELHORIAS)

- Adicionar visualizações mais completas
- Criar pipeline automatizado (ETL)
- Separar código em scripts (src/)
- Exportar dados tratados
- Criar dashboard (Power BI ou Qlik)

--------------------------------------------------

AUTOR

Lucas Feitosa  
Estudante de Sistemas de Informação com foco em Dados

--------------------------------------------------
