# Projeto de Processamento de Dados Simplificado com Power BI

Este é um projeto de análise de dados desenvolvido utilizando o Power BI. O objetivo deste projeto é demonstrar minha capacidade de extração, transformar e visualizar dados de forma eficaz para obter insights valiosos com base nas seguintes etapas e diretrizes:

# Configuração da Infraestrutura na Azure
• Criação de uma instância na Azure para MySQL, configurei uma instância na Azure para hospedar um servidor MySQL.

# Criação do Banco de Dados
•	Utilizei o banco de dados disponível no GitHub para este projeto, importando-o para o servidor MySQL na Azure.
# Integração do Power BI com MySQL na Azure
•	Conectei o Power BI ao servidor MySQL na Azure para acessar os dados do banco de dados.

# Transformação dos Dados
• Verificação de Problemas na Base de Dados
•	Verifiquei a base de dados em busca de problemas e anomalias nos dados que precisavam ser tratados.

# Diretrizes para Transformação dos Dados
1.	Verificação dos Cabeçalhos e Tipos de Dados.
2.	Modificação dos Valores Monetários para o Tipo Double Preciso.
3.	Análise da Existência de Valores Nulos e Remoção quando necessário.
4.	Identificação de Funcionários sem Gerentes com base em nulos em "Super_ssn".
5.	Verificação de Departamentos sem Gerentes e preenchimento das lacunas, se necessário.
6.	Verificação do Número de Horas dos Projetos.
7.	Separação de Colunas Complexas.
8.	Mescla de Consultas Employee e Department para criar uma tabela Employee com os nomes dos departamentos associados aos colaboradores.
9.	Eliminação de Colunas Desnecessárias.
10.	Junção dos Colaboradores com os Nomes dos Gerentes.
11.	Mescla dos Nomes de Colaboradores (Nome e Sobrenome).
12.	Mescla dos Nomes de Departamentos e Localização para auxiliar na criação do modelo estrela em um módulo futuro. Neste caso supracitado, podemos apenas utilizar o mesclar e não o acrescentar por quê?

# Explicação do uso da mescla em vez do acrescentar.
• Porque mesclar serve para unir Colunas de duas tabelas, ou seja, ela trabalha de uma forma colunar. Já o acrescentar consultas ele trabalha de forma linear, seve para você unificar as linhas de tabelas diferentes.

# Resultados
•	Após a transformação dos dados, obtive um conjunto de dados limpo e pronto para análise no Power BI.

# Observações
•	No processo de junção dos colaboradores e nomes dos gerentes, utilizei a mescla de tabelas com Power BI.

# Agrupamento de Dados
•	Realizei o agrupamento dos dados para determinar quantos colaboradores existem por gerente;
• Agrupei também os dados de employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores.
• Os dados das colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores e os dados de nomes de departamentos e localização.

# Limpeza Final
•	Eliminei as colunas desnecessárias de cada tabela, que não serão utilizadas nos relatórios finais.

# Conclusão
Este projeto demonstra minha capacidade de usar o Power BI para coletar, transformar e visualizar dados de forma eficaz, fornecendo insights valiosos para a tomada de decisões. Fique à vontade para explorar o projeto neste repositório.

Se tiver alguma dúvida ou sugestão, não hesite em entrar em contato. Obrigado por verificar este projeto!
