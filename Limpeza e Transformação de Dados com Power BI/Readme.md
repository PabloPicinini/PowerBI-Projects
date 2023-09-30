# Processos Realizados de Transformação dos Dados



## TABELA DEPARTAMENT
    - Tipo alterado da coluna MRG_SSN para inteiro.

## TABELA DEPENDENT
    - Tipo alterado da coluna ESSN  para inteiro.   
 
## TABELA WORKS_ON
    - Tipo alterado da coluna ESSN para inteiro.

## TABELA EMPLOYEE
    - Tipo alterado da coluna SSN para inteiro.
    - Tipo alterado da coluna SUPER_SSN para inteiro.
    - Tipo alterado da coluna SALARY para decimal fixo.
    - Separação da coluna ADRESS em 4 colunas: *Numero*, *Logradouro*, *Cidade* e *Estado*. 

## TABELA DEPARTAMENT
    - Tipo alterado da coluna SSN para inteiro. 

## Mesclagem de consultas
1. Entre tabelas EMPLOYEE e DEPARTAMENT para criar uma tabela employee com o nome dos departamentos associados aos colaboradores, vindo como EMPLOYEE_DEPARTAMENT.
    - Remoção de Colunas desnecessárias.
    - Mesclagem do Nome e Sobrenome em apenas uma coluna.
2. Consulta dos Colaboradores e Respectivos nomes dos Gerentes, pela prórpia Tabela EMPLOYEE, vindo como EMPLOYEES_X_GERENTES.
    - Remoção de Colunas desnecessárias.
    - Mesclagem do Nome e Sobrenome em apenas uma coluna.
3. Consulta dos nomes de Departamentos e Localização, vindo como DEPARTAMENT_LOCAL.
    - Remoção de Colunas desnecessárias.
4. Consulta agrupada para saber quantos colaboradores existem por gerente, vindo como AGRUPAR_EMPLOYEES_POR_GERENTE
    - Remoção de Colunas desnecessárias.


## Análises:
    - Na coluna SUPER_SSN da Tabela Employee está presente um valor nulo, o qual é um colaborador sem gerente.  
    - O Colaborador James está sem Gerente, pois é gerente de cargo mais alto.
    - Todos os departamentos possuem gerentes.
    - Há um projeto com horas zeradas.
    - A Mesclagem é como se fosse um join no SQL, trazendo informações de duas ou mais tabelas em apenas uma visualização. Já o atribuir é usada para criar uma nova coluna em uma tabela já existente.





 
