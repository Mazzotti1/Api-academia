Objetivo


Objetivo desse projeto foi criar uma Api Restfull para gerenciamento de alunos, avaliações e matriculas de uma academia 


 Aprendizado
Configurações do banco de dados PostgreeSQL
Anotações de entidades
Crud

📚 CRUD (Create, Read, Update, Delete):

🔺 Create:
Criação (Create): Na criação de um novo usuário, por exemplo, o método POST seria utilizado para enviar as informações do novo usuário (como nome, email e senha) para o servidor, que então persistiria esses dados no banco de dados PostgreSQL.


🔺 Read:
Leitura (Read): Para buscar informações de um usuário já existente, poderíamos utilizar o método GET, que retornaria os dados desse usuário armazenados no banco de dados.


🔺 Update:
Atualização (Update): Caso um usuário queira atualizar alguma informação de sua conta, como seu endereço, poderíamos utilizar o método PUT, que enviaria as novas informações para o servidor e atualizaria os dados do usuário correspondente no banco de dados.


🔺 Delete:
Exclusão (Delete): Se um usuário quiser excluir sua conta, por exemplo, o método DELETE seria utilizado para enviar uma requisição ao servidor para remover os dados do usuário correspondente no banco de dados PostgreSQL.


📚 Anotações de entidade


As anotações de entidade em Java são usadas para mapear classes Java para tabelas em um banco de dados relacional, permitindo que a aplicação acesse e manipule os dados armazenados. Algumas das anotações mais comuns incluem:

@Entity: indica que a classe representa uma entidade de banco de dados.
@Table: permite especificar o nome da tabela correspondente à classe.
@Id: indica que um campo representa a chave primária da tabela.
@Column: permite especificar o nome da coluna correspondente a um campo.
@GeneratedValue: indica que o valor da chave primária é gerado automaticamente pelo banco de dados.
Essas anotações permitem que o desenvolvedor descreva a estrutura de seus dados usando classes Java e se beneficiem dos recursos do JPA (Java Persistence API) para criar, ler, atualizar e excluir registros de banco de dados.







🛠 Ferramenta utilizada

 IntelliJ e PostgreeSQL
