# **RECURSOS_HUMANOS**

Repositório desenvolvido para um trabalho em grupo do curso **TDS — Técnico de Desenvolvimento de Sistemas**. O projeto consiste na criação de uma base de dados SQL para uma empresa fictícia de Recursos Humanos, permitindo armazenar e consultar informações relacionadas com empresas, candidatos, vagas e candidaturas.

## Tecnologias utilizadas

| Nome | Versão |
|-------|--------|
| MySQL | 8.0 |
| SQL | — |
| MySQL Workbench | — |

## Criação da Base de Dados

O projeto consiste na criação e implementação de uma base de dados relacional para uma empresa fictícia de Recursos Humanos.

Foram desenvolvidas várias tabelas para armazenar informações sobre:

- Empresas
- Recrutadores
- Candidatos
- Vagas
- Candidaturas
- Entrevistas
- Qualificações
- Experiência profissional
- Formação académica
- Histórico de candidaturas

### Modelo Relacional

O projeto possui também um modelo relacional que representa as relações entre as diferentes tabelas da base de dados.

## Tarefas realizadas

- Criar as tabelas da base de dados
- Definir as chaves primárias e estrangeiras
- Inserir dados fictícios
- Criar consultas SQL
- Estabelecer os relacionamentos entre as tabelas
- Desenvolver o modelo relacional

## Tarefas por fazer

- [ ] Adicionar novas consultas SQL
- [ ] Testar todas as relações entre as tabelas
- [ ] Melhorar a documentação do projeto
- [ ] Adicionar novos dados para testes

## Configuração

Para utilizar o projeto, é necessário ter o **MySQL** ou uma ferramenta compatível, como o MySQL Workbench.

### Passos para executar

1. Instalar o MySQL.
2. Abrir o MySQL Workbench.
3. Executar o ficheiro `Cod_database_next_people.sql` para criar a estrutura da base de dados.
4. Executar os ficheiros de dados e chaves estrangeiras.
5. Executar o ficheiro `Consultas_dados.sql` para testar as consultas.
6. Verificar os resultados das consultas na base de dados.

## Repositório

O código e os ficheiros do projeto estão disponíveis no **GitHub**:

[RECURSOS_HUMANOS — GitHub](https://github.com/BrunaStefanni/RECURSOS_HUMANOS.git)

### Autores

- Bruna Leite
- Tatiane Medeiros
- Gabriela Viana


**Projeto desenvolvido em grupo para fins académicos.**

*Este projeto foi desenvolvido no âmbito da disciplina de Base de Dados SQL.*

*E este README foi desenvolvido para tarefa 2 no âmbito da disciplina de Git-GitHub.*




### Exemplo de consulta utilizada no projeto:

```sql
SELECT * FROM CANDIDATO;

