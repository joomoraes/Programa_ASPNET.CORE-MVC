# Programa_ASPNET.CORE-MVC
Programação completa separada por branchs de metódologia pelas quais você poderá acompanhar as etapas de desenvolvimento e a atribuição ou inserção de novas técnologias ou código referente ao desenvolvimento da aplicação

## Nivelamento Entity Framework

**DbContext** : um objeto DBContext encapsula uma sessão com o banco de dados para um determinado modelo de dados (representado por DBSet’s).
É Usado para consultar e salvar entidades no banco de dados 
Define quais entidades farão parte do modelo de dados dos sistema 
Pode definir várias configurações 
É uma combinação dos padrões Unity of Work e Repository 
<br><br>**Unity Work**: “mantém uma lista de objetos afetas por uma transação e coordena a escrito de mudanças e trta possíveis problemas de concorrência” – *Martin Fowler*
<br><br>**Repository**: “define um objeto capaz de realizar operações de acesso a dados (consultar, salvar, atualizar, deletar) para uma entidade
<br><br>**DBSet<TEntity>**:  representa a coleção de entidades de um dado tipo em um contexto. Tipicamente corresponde a uma tabela do banco de dados.
