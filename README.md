# PowerBI

Alura Challenge BI

A proposta Alura Challenge BI é que seus alunos demonstrem suas competências e habilidades adquiridas durante seus cursos em Business Intelligence, utilizando a plataforma Power BI. 
O projeto é realizado em 4 semanas e são divididos da seguinte forma:
Semana 01: Painel do Desafio de Logística 
Semana 02: Painel de Marketing 
Semana 03 e 04: Painel do Desafio Financeiro

Foi utilizado a plataforma Trello para controlar o andamento das atividades de forma otimizada.

DASHBOARD LOGÍSTICA
Estudo de caso: A pessoa que gerencia a área de logística da Alura Log, está enfrentando algumas mudanças em sua área por conta do aumento da demanda dos serviços de logística no período da pandemia. Ela quer manter a qualidade de seu serviço, mas para isso precisa acompanhar constantemente as métricas do seu departamento para tomar as melhores decisões. Quando nos contou isso, analisamos que para auxiliar nesse desafio precisaremos fazer um dashboard para logística. Para isso, vamos visualizar algumas métricas muito importantes para a área.

Inicialmente é feito a importação das tabelas, sendo elas:
1.	tabela pedidos - contém o registro de todos os pedidos feitos pelos clientes.
2.	tabela produtos - contém os produtos cadastrados e seus valores.
3.	tabela veículos - contém veículos registrados que fazem o transporte dos produtos
4.	tabela estoque - contém o registro de estoque dos produtos por mês

Foram realizados todos os processos de ETL no Power Query, como por exemplos:
Na tabela produtos foi alterado o tipo da coluna preço para decimal fixo, alterado os campos da coluna categoria: removendo os _ e extraindo os dois primeiros caracteres para ficar somente o nome da categoria – para isso foi necessário usar a opção extrair texto após delimitador
Também foram renomeadas colunas, removidas células vazias.

Como se trata de um projeto da empresa Alura, procurei a paleta de cores referente ao logo por meio do site: https://www.canva.com/colors/color-palette-generator/
![image](https://user-images.githubusercontent.com/104572672/177175681-307214a9-acbe-4a3a-8d85-93c23953f3a1.png)

