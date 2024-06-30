# Projeto desenvolvido para o bootcamp "Python Data Analytics" proposto pela DIO

**Data: 14/03/2024**

One of the proposed challenge projects of DIO's Data Analytics Bootcamp (Squadio) consists to taking a small fictitious dataset and create a visualization.

Valuing simple but concise visual elements - which don't attract attention otherwise to important graphs and indicators - I created this dashboard using a test dataset called Financial Sample, provided by Microsoft.

In this dashboard you'll find:
- Buttons to switch between charts.
- Buttons to switch between reports.
- Buttons to clear applied filters.
- DAX measures that calculate the gain/loss of sales at determined period.
- Dynamic visualization with the tooltip that uses the previously report listed (DAX), which allows to analyze the trimestral comportament.

--

Um dos desafios de projeto propostos do bootcamp de Data Analytics da DIO consiste em pegar uma pequena base de dados fictícios e dar uma visualização.

Prezando por elementos visuais simples, mas concisos - que não atraem a atenção senão para os gráficos e indicadores importantes - construí esse dashboard utilizando a base de dados teste Financial Sample fornecida pela Microsoft.

Nesse dashboard é possível encontrar:
- Botões que alternam visualizações entre gráficos;
- Botões que alternam visualizações entre relatórios;
- Botões que limpam os filtros aplicados;
- Medida DAX que calcula o crescimento/perda de Faturamento em determinado período;
- Visualização dinâmica com dica de ferramenta de relatório construído com a medida anterior, evidenciando o comportamento trimestral.

## Primeiros passos

- Transformação de Dados com Power Query;
  - Verificada a qualidade dos dados: Todas as colunas com 100% dos dados preenchidos;
  - Alteração de tipos de dados:
    - Alterado "Manufacturing Price" e "Sale Price" para número decimal, por se tratar de valor monetário;

- Todos os critérios foram desenvolvidos no projeto.
- Não foi possível publicar no workspace do Power BI Service, pois não possuo conta corporativa e nem de estudante.
  - Projeto entregue exclusivamente neste repositório do GitHub.

**Data: 28/03/2024**

## Melhorias de layout:

- Adição de ícones para os cartões de detalhes;
- Cores mais neutras e suaves para que o foco seja todo nas informações e gráficos;
- Títulos com destaques para tornar a divisão dos gráficos mais evidente e compreensível;
- Escolha de fontes para deixar a dashboard mais agradável e com melhor legibilidade;

## Melhorias de utilização:

- Adicionado um seletor que permite escolher qual relatório utilizar.
