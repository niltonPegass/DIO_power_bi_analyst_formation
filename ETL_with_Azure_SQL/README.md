# LIMPEZA E TRATAMENTO DE DADOS

## dependent
- Exclusão de coluna com metadados
- Alteração de tipo:
	- Essn: número inteiro

## departament
- Exclusão de colunas com metadados
- Alteração de tipo:
	- Mgr_ssn: número inteiro

## dept_locations
- Exclusão de colunas com metadados

## employee
- Exclusão de colunas com metadados
- Alteração de tipo:
	- Super_ssn: número inteiro
	- Salary: número decimal fixo (moeda)
	- Ssn: número inteiro
- Divisão da coluna "address":
	- address_num: inteiro
	- address: texto
	- address_state: texto
	- address_state: TX substituído para Texas
- Mesclagem das colunas Fname, Minit, Lname > Name
- Exclusão das colunas de nomes

## works_on
- Exclusão de colunas com metadados
- Alteração de tipo:
	- Essn: número inteiro

## project
- Exclusão de colunas com metadados

# PERSONALIZAÇÕES

- Criação de nova tabela (`dept_name_locations`) por meio de "Mesclar Consultas como Novas" para obter campo associando Dname e Dlocation (Nome do Departamento e Localização do Departamento).
	- Nessa personalização não é possível utilizar o recurso "Acrescentar Consultas", pois nesse caso ele adiciona campos com títulos, tipos e dados diferentes, fazendo com que a nova tabela criada seja inconsistente para a criação de relatórios
