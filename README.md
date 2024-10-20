### Aprimorando conhecimentos com o Sequelize

- A partir de uma lista de requisitos, aprimorado funcionalidades da API.
- Soft delete: Paranoid
- Filtrar o Overfetching (trazer mais dados do que precisa) através de um escopo no modelo.
- Tratamento de erro para email inválido (biblioteca validate: isEmail) do Sequelize
- Mock (função externa) de validação dentro do objeto validate para o CPF
- - Uso de helper functions para validação de dados, formatação de dados de saída, conversão de tipo de dados, etc.
- Consultar todas as matriculas confirmadas de forma rápida.
- Consultar turmas por intervalo de data (para não receber informações desnecessárias (turmas antigas))
- Consultar por query params (strings)
- Saber quais cursos tem está lotado (validar quantas matrículas possui através de do Sequelize.literal para passar uma query SQL personalizada.)
- Uso de transactions para o gerenciamento de atualizações no banco de dados através do Sequelize. (mudança total ou rollback)
