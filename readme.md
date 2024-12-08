# Comparando Resultados do TCC com Artigo Científico

Este repositório contém os dados, códigos utilizando o notebook do python e análises realizados no contexto do Trabalho de Conclusão de Curso (TCC) denominado FunExpression, cujo objetivo principal foi comparar os resultados obtidos com os resultados apresentados em um artigo científico de referência.

## Objetivo do Projeto

O objetivo deste repositório é documentar as etapas e métodos utilizados para:

1. **Realizar duas avaliações distintas**: Estas avaliações foram planejadas para reproduzir o método do artigo de referência e avaliar a consistência dos resultados.
2. **Comparar os resultados**: Identificar semelhanças, divergências e possíveis fatores que contribuem para as diferenças observadas entre os resultados obtidos e os do artigo.

## Estrutura do Repositório

- **`avaliacao_1/`**: Contém os conjuntos de dados utilizados na avaliação 1 que foi feita entre o pipeline do galaxy e o artigo. Estes incluem:
  - `count_genes_up.ipynb`: código com a contagem de genes upregulateds apenas no artigo, apenas no galaxy e na intersecção de ambos.
  - `count_genes_down.ipynb`: código com a contagem de genes downregulateds apenas no artigo, apenas no galaxy e na intersecção de ambos.
  - `genes_up.csv`: planilha com os genes upregulateds do artigo
  - `genes_down.csv`: planilha com os genes downregulateds do artigo
  - `avaliacao_1.png`:diagrama de venn com os genes classificados

- **`avaliacao_2/`**: Contém os conjuntos de dados utilizados na avaliação 2 que foi feita entre o pipeline do FunExpression e o artigo. Estes incluem:
  - `id_1 até id_5`: pastas de cada experimento de acordo com a numeração dos artigos na monografia
  - `article_data`: contém o conjunto de dados do artigo
    - `article.txt`: genes upregulateds e downregulateds do artigo
    - `genes_up_article.csv`: planilha com os genes upregulateds do artigo
    - `genes_down_article.csv`: planilha com os genes downregulateds do artigo
    - `get_up_down_genes_by_article`: código que faz a classificação dos genes do artigo entre upregulated e downregulated e cria uma planilha para cada classificação de gene

  - `funexpression_data`: contém o conjunto de dados do funexpression
    - `funexpression.csv`: genes upregulateds e downregulateds do funexpression
    - `genes_up_funexpression.csv`: planilha com os genes upregulateds do funexpression
    - `genes_down_funexpression.csv`: planilha com os genes downregulateds do funexpression
    - `get_up_down_genes_by_funexpression`: código que faz a classificação dos genes do funexpression entre upregulated e downregulated e cria uma planilha para cada classificação de gene

  - `funexpression_data`: contém o conjunto de dados do funexpression
  - `count_genes_up.ipynb`: código com a contagem de genes upregulateds apenas no artigo, apenas no galaxy e na intersecção de ambos.
  - `count_genes_down.ipynb`: código com a contagem de genes downregulateds apenas no artigo, apenas no galaxy e na intersecção de ambos.
  - `genes_up.csv`: planilha com os id dos genes upregulateds do artigo e de funexpression
  - `genes_down.csv`: planilha com os id dos genes downregulateds do artigo e de funexpression
  - `avaliacao_2.png`:diagrama de venn com os genes classificados




## Metodologia

As avaliações foram conduzidas seguindo as diretrizes metodológicas descritas na monografia na seção metodologia.


## Como Usar Este Repositório

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/comparacao-resultados-tcc.git
   ```

2. Navegue até o diretório apropriado para os scripts ou dados que deseja utilizar.

3. Execute os scripts clicando na opção RunAll do notebook.

## Resultados Obtidos

Os resultados comparativos são impressos ao fim de cada notebook e também podem ser visualizados a partir de maneira gráfica pelo diagrama de venn contido em cada diretório.

## Referências

- **Artigo de Referências**: 
    - https://doi.org/10.1186/s12863-024-01257-3
    - https://doi.org/10.1371/journal.pgen.1005509

## **Código do FunExpression**:
  - https://github.com/Adeonita/funexpression


## Contribuições

Contribuições são bem-vindas! Se você identificar melhorias ou desejar compartilhar ideias, abra um *issue* ou envie um *pull request*.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
