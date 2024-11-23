Análise de Dados de Vendas
📋 Introdução
Este projeto foi desenvolvido para simular e analisar dados fictícios de vendas, gerando insights úteis para estratégias de marketing. Utiliza Python para processar dados, criar visualizações e realizar consultas SQL. O objetivo principal é fornecer uma base prática para análise de vendas com gráficos, cálculos e planos de ação.

📂 Estrutura do Repositório
A organização do repositório é a seguinte:

/
├── relatorio_insights.pdf          # Relatório com os principais insights obtidos
├── Teste_Analytics_MarcoSilva.ipynb  # Notebook com o código completo
├── Documentação_Código.pdf         # Detalhes técnicos e explicação do código
├── consultas_sql.sql               # Arquivo com consultas SQL geradas
├── README.md                       # Arquivo de documentação do projeto

🛠 Como Executar os Scripts:

1. Requisitos
Certifique-se de que o Python está instalado na versão 3.8 ou superior. As bibliotecas necessárias são:
- pandas
- numpy
- matplotlib
- 
2. Instalação das Dependências:
Execute o seguinte comando no terminal para instalar as dependências:

bash
Copiar código
pip install pandas numpy matplotlib

3. Executando o Notebook:
   
- Faça o download do arquivo Teste_Analytics_MarcoSilva.ipynb.
- Abra o arquivo no Jupyter Notebook, VS Code ou Google Colab.
- Execute as células do notebook sequencialmente para:
- Gerar os dados fictícios.
- Realizar análises exploratórias.
- Criar gráficos de tendências.
- Gerar insights.
  
📊 Insights Obtidos

Categorias Mais Lucrativas:
As categorias de produtos com maior receita foram identificadas com base na soma total de vendas.
Plano de Ação: Expandir a variedade de itens e ajustar o estoque para atender à alta demanda.
Sazonalidade nas Vendas:

O gráfico de séries temporais identificou picos de vendas em meses específicos, indicando sazonalidade.
Plano de Ação: Planejar campanhas promocionais nos períodos de alta e ajustar a alocação de recursos.
Produtos com Baixa Performance:

Produtos menos vendidos foram destacados para análise de melhorias ou ajustes.
Plano de Ação: Criar combos promocionais e revisar a precificação.
Média de Vendas por Transação:

🛠 Consultas SQL:

As consultas SQL foram geradas e estão no arquivo consultas_sql.sql. Elas incluem:

1. Listar produtos e categorias com maiores vendas totais.
2. Identificar produtos com menor venda em junho de 2024.
