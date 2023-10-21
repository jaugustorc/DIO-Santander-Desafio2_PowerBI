# DIO-Santander-Desafio2_PowerBI

## Processamento de Dados Simplificado com Power BI

Este repositório contém a solução para o desafio do Módulo 3 - Processamento de Dados Simplificado com Power BI. O objetivo deste desafio é criar um fluxo de processamento de dados com o Power BI, envolvendo a criação de uma instância na Azure para MySQL, integração de dados, transformações e criação de consultas.

## Passos do Desafio

### 1. Criação de uma instância na Azure para MySQL
- Crie uma instância na Azure para MySQL conforme as instruções do curso.

### 2. Criar o Banco de dados com base disponível no GitHub
- Utilize a base de dados disponível no [GitHub](https://github.com/seu-usuario/nome-do-repositorio) e crie o banco de dados.

### 3. Integração do Power BI com MySQL no Azure
- Realize a integração do Power BI com o MySQL na Azure para acessar os dados.

### 4. Verificar problemas na base a fim de realizar a transformação dos dados
- Analise a base de dados em busca de problemas que requerem transformação.

## Diretrizes para Transformação dos Dados

1. Verifique os cabeçalhos e tipos de dados.
2. Modifique os valores monetários para o tipo double preciso.
3. Verifique a existência de valores nulos e analise a remoção.
4. Identifique os funcionários com valores nulos em Super_ssn, que podem ser gerentes.
5. Verifique se há algum colaborador sem gerente.
6. Verifique se há algum departamento sem gerente. Se houver, preencha as lacunas.
7. Verifique o número de horas dos projetos.
8. Separe colunas complexas.
9. Mescle consultas de funcionários e departamentos para criar uma tabela que associe os nomes dos departamentos aos colaboradores. A base será a tabela de funcionários.
10. Elimine as colunas desnecessárias.
11. Realize a junção dos colaboradores com os nomes dos gerentes. Especifique a query SQL, se utilizada.
12. Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores.
13. Mescle os nomes de departamentos e localizações para criar combinações únicas.
14. Explique por que a mesclagem é preferível à atribuição.
15. Agrupe os dados para saber quantos colaboradores existem por gerente.
16. Elimine as colunas desnecessárias de cada tabela, que não serão usadas no relatório.

## Conclusão

Este desafio visa aprimorar suas habilidades em processamento de dados e criação de consultas com o Power BI. Siga as diretrizes e etapas descritas acima para concluir o desafio com sucesso. Este repositório contém todos os recursos necessários para o desenvolvimento do projeto.

Boa sorte e continue aprendendo! 😎
