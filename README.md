# Modelando-um-Dashboard-de-E-commerce-com-Power-BI-Utilizando-F-rmulas-DAX


# Descrição do desafio:
Utilizar a tabela única de Financial Sample para criar as tabelas dimensão e fato do modelo baseado em star schema. O processo consiste na criação das tabelas com base na tabela original. A partir da cópia serão selecionadas as colunas que irão compor a visão da nova tabela. Sendo assim, a partir da tabela principal (fato) serão criadas as outras tabelas (dimensão).

Financials_origem (modo oculto - backup)
F_Vendas(fato)
D_Produtos(dimensão)
D_Produtos_Detalhes(dimensão)
D_Detalhes(dimensão)
D_Calendário(dimensão)

# Descrição dos passos usados:
Importação de dados da planilha Financial Sample para o Power BI Desktop;
Duplicação da tabela financials e geração da tabela Financials_origem (backup);
Em Modelagem, criação da tabela F_Vendas (fato);
A seguir, criação das tabelas 'dimensão': D_Produtos, D_Produtos_Detalhes, D_Detalhes, D_Descontos e D_Calendario;
Obs.: A tabela D_Calendario foi construída conforme orientações: Os Primeiros Passos com DAX;
Transformação, composição e definição das colunas para as tabelas: D_Produtos, D_Produtos_Detalhes, D_Descontos e D_Detalhes;
Organização, links e definição dos relacionamentos entre as tabelas conforme o Star Schema;
