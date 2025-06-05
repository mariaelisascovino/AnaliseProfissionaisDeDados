# AnaliseProfissionaisDeDados
Neste projeto, desenvolvido no curso da PrograMaria, foi realizada uma análise de dados desde a extração e análise exploratória, transformação e mesclagem de diversas fontes até o upload e criação da visualização via Looker. Uso de Excel, Google Sheets, bibliotecas Python, SQL, SQLite e Looker. 

A base de dados: Consiste em dados de pesquisa sobre profissionais de TI e informações sobre gênero, etnia, nível de formação, nível de cargo, dentre outras informações de perfil profissional. 

Link do Colab: https://colab.research.google.com/drive/1tx_vyry8mSeTFCgDxtmEsjL4xUpvOO0g?usp=sharing
Link do Looker: https://lookerstudio.google.com/reporting/c4862435-5991-4ee2-b9bf-b1c41e6f9ea5


1) ANÁLISE DE DADOS VIA NOTEBOOK COLAB
   
Realizada análise usando bibliotecas Python permitindo diferentes etapas e formas de manipulação e interpretação dos dados: leitura, visualização e exploração inicial do dataframe, remodelagem e análise exploratória dos dados, estatística, tratamento de valores nulos e outliers, remoção de duplicatas,  métodos de Featuring engineering, conexão com Google Drive e SQLite, visualização de gráficos e boxplots, correlação e exportação dos dados. 

🧠 Etapas Estratégicas no Tratamento e Análise de Dados

1. Importação e Carregamento dos Dados

- Escolha da biblioteca adequada (pandas) para manipulação.
- Leitura de arquivo Excel com estrutura tabular.
- Primeira exploração com .head(), .info() e .describe() para entender o formato, tipos e qualidade dos dados.

Objetivo: Compreender a estrutura geral do dataset e possíveis inconsistências.

2. Diagnóstico e Qualidade dos Dados
   
- Verificação de valores nulos.
- Identificação de colunas irrelevantes, mal nomeadas ou com dados inúteis.
- Contagem de valores únicos para entender variabilidade e possíveis problemas (ex: inconsistências de escrita).

Objetivo: Avaliar o que precisa ser limpo, padronizado ou descartado.

3. Limpeza e Padronização

- Renomeação de colunas para tornar os nomes mais intuitivos.
- Exclusão de colunas não utilizadas ou redundantes.
- Conversão de colunas para tipos apropriados (ex: booleanos para inteiros).
- Criação de novas colunas com dados transformados ou categorizados.

Objetivo: Garantir que os dados estejam prontos para análises e visualizações sem ruído.

4. Tratamento de Duplicatas e Inconsistências

- Checagem de duplicidade de registros (ex: IDs).
- Verificação e tratamento de linhas com dados ambíguos ou repetidos.
- Objetivo: Assegurar que cada linha represente uma entidade única e válida.

5. Organização e Reestruturação dos Dados

- Reorganização de colunas para facilitar leitura e comparação.
- Agrupamentos estratégicos para identificar padrões por categoria (ex: por gênero, região, etc).
- Preparação para análises quantitativas e qualitativas.

Objetivo: Tornar os dados mais legíveis e prontos para serem explorados com visualizações e métricas.

6. Exploração e Análises Iniciais

- Aplicação de filtros e contagens por categorias.
- Exploração de proporções e frequências com base em colunas relevantes.
- Objetivo: Identificar tendências, perfis, padrões ou desigualdades no conjunto de dados.

7. Criação de Variáveis Derivadas

- Derivação de colunas binárias ou categóricas com base em colunas originais (ex: respostas booleanas convertidas em 0/1).
- Preparação de colunas para futuras análises estatísticas ou machine learning.

Objetivo: Enriquecer o dataset com variáveis que potencializam insights.

🎯 Conclusão
O notebook segue um fluxo essencial de ETL (Extract, Transform, Load), com foco em limpeza, estruturação e exploração inicial. Essas etapas são fundamentais para garantir que análises futuras sejam feitas com dados confiáveis, bem estruturados e significativos.


2) LOOKER STUDIO

Nesta etapa foi usado o Looker Studio como ferramenta de visualização dos dados e pontos chaves da análise voltado a gênero e etnia.

<img width="713" alt="looker1" src="https://github.com/user-attachments/assets/942c183a-e2e8-4d90-b70c-d5764d1353fa" />
<img width="713" alt="looker2" src="https://github.com/user-attachments/assets/1667a939-63ce-4f78-bfa1-74d49691c019" />
<img width="711" alt="looker3" src="https://github.com/user-attachments/assets/42fdadf3-ac84-4378-aa15-3cd71a77fd03" />


🧠 Etapas da Criação do Relatório:

1.Coleta de Dados

- Reunião de informações de diversas fontes sobre profissionais de dados.

objetivo: garantir fontes confiáveis e consistentes para a análise.

2. Análise Estatística
   
 - Uso de ferramentas estatísticas para analisar os dados coletados.

objetivo: o Looker permite a criação de diversas análises e cálculos dentro da ferramenta.

3. Visualização

- Criação de gráficos e tabelas utilizando o Looker para facilitar a interpretação dos dados.

objetivo: o Looker disponibiliza diversas ferramentas e modelos para criar análises visuais.

4. Interpretação

- Análise dos resultados para tirar conclusões significativas sobre a diversidade no setor.

objetivo: o mais importante são as conclusões e insights que podem ser extraídos da análise. 

5.Relato

-Compilação das análises em um documento estruturado que destaca as principais descobertas e recomendações.

objetivo: reunir, num único arquivo, as principais análises de forma interativa e simples. 

🎯 Conclusão

O relatório fornece insights valiosos sobre a diversidade no campo dos dados no Brasil, destacando desigualdades de gênero e étnicas, e sugere que ferramentas como o Looker podem potencializar a análise e apresentação de dados, promovendo uma melhor compreensão e tomada de decisões informadas.
