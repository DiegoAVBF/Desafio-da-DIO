# Desafio-da-DIO
Um repositório com o intuito de disponibilizar principais conceitos de SQL e NOSQL

Dentro da Vida de um Engenheiro de Dados é importante conhecer as principais ferramentas do mercado, não só em questão de manuseio mas tambêm em suas definições de criações, seus principais pontos positivos e negativos e como melhor utilizar os positivos e como melhor se adaptar aos negativos e para isso a solução normalmente é a utilização de multiplas SGBDs de diferentes tipos, como SQL e NOSQL.

O SQL exige que você use esquemas (arquiteturas visuais e lógicas de uma base de dados) pré-definidos para determinar a estrutura dos seus dados antes de trabalhar com eles.Além disso, todos os seus dados devem seguir a mesma estrutura. Isso pode requerer uma preparação inicial significante e pode ser que uma mudança na estrutura seja tanto difícil quanto disruptiva para todo o seu sistema.

Uma base de dados NoSQL, por outro lado, tem um esquema dinâmico para dados não estruturados, e o dado é armazenado em várias formas: pode ser orientado a coluna, orientado a documento, baseado em grafos ou organizado como chave-valor. Essa flexibilidade permite que:

* Você crie documentos sem ter que definir sua estrutura primeiro;
* Cada documento tenha sua própria estrutura única;
* A sintaxe varie de base de dados para base de dados;
* Você adicione campos sempre que precisar.

## Escalabilidade

Na maioria das situações, as bases de dados SQL são verticalmente escaláveis, o que significa que você pode aumentar o carregamento em um servidor melhorando coisas como CPU, RAM ou SSD.

As bases de dados NoSQL, por sua vez, são horizontalmente escaláveis. Isso quer dizer que você suporta muito mais tráfego por sharding (particionamento de dados), ou seja, adicionando mais servidores na sua base de dados NoSQL. O segundo pode ficar maior e mais poderoso, tornando as bases de dados NoSQL a escolha de preferência para conjuntos de dados maiores ou em mudança constante.

## Estrutura

As bases de dados SQL são baseadas em tabelas, enquanto que as bases de dados NoSQL podem ser baseadas em documentos, pares de chave-valor, grafos ou orientados a colunas. Isso torna as bases de dados SQL relacionais opções melhores para aplicações que requerem transações retornando várias colunas — como um sistema de contabilidade — ou para sistemas legados que foram criados em uma estrutura relacional.

Alguns exemplos de bases de dados SQL incluem o MySQL, Oracle, PostgreSQL e Microsoft SQL Server. Exemplos de bases de dados NoSQL incluem MongoDB, BigTable, Rediz, RavenDB, Cassandra, HBase, Neo4j e CouchDB.

Conseguir identificar a necessidade da utilização de cada um de acordo com os problemas encontrados no dia a dia do trabalho e de uma forma cujo os dados fiquem de facil acesso as pessoas que irão consultalos e extremamente importante para um Engenheiro de Dados.
