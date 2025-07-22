**Seleção e Agrupamento de Dados com Pandas**

Este repositório contém um Jupyter Notebook focado em técnicas de seleção e agrupamento de dados utilizando a biblioteca Pandas em Python. É um recurso ideal para quem busca aprimorar suas habilidades em manipulação e análise de dados.

**Conteúdo do Notebook**

O notebook pandas_selecao_e_agrupamento.ipynb abrange os seguintes tópicos e habilidades:

**Importação e Manipulação de Dados:**

Importar dados de abas específicas de arquivos Excel para DataFrames Pandas.

Encontrar valores únicos em colunas de um DataFrame usando o método unique().

Filtrar dados com seleção booleana.

Remover colunas de uma tabela com o método drop().

**Transformação e Agrupamento:**

Transformar dados do formato "wide" para "long" e entender as diferenças entre eles.

Construir agrupamentos de dados com o método groupby().

Visualizar grupos gerados pelo groupby() e aplicar métodos de agregação.

Construir gráficos de barras utilizando o método plot().

**Análise Avançada e Visualização:**

Construir agrupamentos a partir de mais de uma informação simultaneamente.

Selecionar dados em DataFrames multi-index.

Alterar a posição dos níveis hierárquicos dos índices em um DataFrame.

Selecionar índices onde o valor for máximo com o método idxmax().

Construir tabelas de pivô com o método pivot_table().

Criar múltiplos gráficos a partir de um DataFrame com várias colunas usando subplots.

**Processamento de Strings e Integração de Dados:**

Filtrar valores contendo parte de uma string em colunas de um DataFrame usando str.contains().

Criar colunas com base em dados de outras colunas usando o método assign().

Utilizar expressões regulares para buscar padrões textuais em strings.

Substituir parte de uma string em valores de uma coluna com o método replace().

Unir conjuntos de dados com o método merge().

Construir gráficos de barras e dispersão interativos com a biblioteca plotly.

Como Utilizar
Para rodar este notebook em sua máquina, siga os passos abaixo:

Clone o Repositório:

Bash

git clone <URL_DO_SEU_REPOSITORIO>
cd <NOME_DO_SEU_REPOSITORIO>
##Crie e Ative um Ambiente Virtual (Opcional, mas Recomendado):

Bash

python -m venv venv
# No Windows
.\venv\Scripts\activate
# No macOS/Linux
source venv/bin/activate
Instale as Dependências:
Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las com pip:

Bash

pip install pandas openpyxl matplotlib plotly nbformat
Execute o Jupyter Notebook:

Bash

jupyter notebook pandas_selecao_e_agrupamento.ipynb
Isso abrirá o notebook em seu navegador, onde você poderá executar as células e explorar o código.

Contribuição
Contribuições são sempre bem-vindas! Se você tiver sugestões, melhorias ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
