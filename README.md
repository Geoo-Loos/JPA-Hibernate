```markdown
# JPA & Hibernate - Persistência de Dados em Java

Este projeto demonstra a implementação da **JPA (Java Persistence API)** utilizando o **Hibernate** como framework ORM (Object-Relational Mapping). O objetivo principal é gerir a persistência de objetos Java num banco de dados relacional de forma eficiente e organizada.

## 🚀 Tecnologias Utilizadas
* **Java 17**: Linguagem base do projeto.
* **JPA / Hibernate**: Para o mapeamento das entidades e gestão do ciclo de vida dos objetos.
* **Maven**: Gestão de dependências e automação de build.
* **MySQL/MariaDB**: Banco de dados para armazenamento persistente.

## 📂 Estrutura do Projeto
O projeto segue a estrutura padrão do Maven:
* `src/main/java`: Contém as entidades, repositórios e a lógica de aplicação.
* `src/main/resources/META-INF/persistence.xml`: Configurações de conexão com o banco de dados e propriedades do Hibernate.

## ⚙️ Funcionalidades
* Mapeamento de entidades com anotações JPA (`@Entity`, `@Table`, `@Id`, etc.).
* Operações de CRUD (Create, Read, Update, Delete).
* Configuração de relacionamentos entre objetos.
* Uso do `EntityManager` para controlo de transações.

## 🛠️ Como Executar
1. Certifique-se de ter o **Maven** e o **JDK 17** instalados.
2. Configure a conexão do banco de dados no ficheiro `persistence.xml`.
3. Execute o comando para compilar o projeto:
   ```bash
   mvn clean install
