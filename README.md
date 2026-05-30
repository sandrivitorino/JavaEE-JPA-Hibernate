# JPA and Hibernate Fundamentals

In this module, I studied the fundamentals of object-relational mapping (ORM) in Java using JPA and Hibernate.

The goal was to understand how Java objects can be mapped and persisted into relational databases without manually writing SQL for every operation.

## Topics Covered
- Object-relational mapping (ORM)
- JPA (Java Persistence API)
- Hibernate
- Entity mapping
- Persistence context
- Identity map
- Lazy loading
- EntityManager
- EntityManagerFactory
- Maven dependencies
- MySQL integration
- `persistence.xml`
- Entity annotations
- Object persistence

## Key Concepts
- JPA is the standard Java specification for object-relational mapping.
- Hibernate is one of the most popular implementations of JPA.
- ORM allows Java objects to be stored and retrieved from relational databases.
- `EntityManager` is responsible for database operations involving entities.
- `EntityManagerFactory` creates instances of `EntityManager`.
- Entity classes must be mapped using annotations such as `@Entity` and `@Id`.
- The persistence context manages the lifecycle of entities during database operations.

## Exercises
The exercises focused on creating a simple application using JPA and Hibernate.

Some examples included:

- Creating entity classes
- Mapping Java objects to database tables
- Configuring JPA with `persistence.xml`
- Connecting a Java application to MySQL
- Persisting objects into the database
- Using EntityManager to manage entities

One of the practical activities involved creating a `Pessoa` entity and persisting its data into a MySQL database using JPA and Hibernate.

These exercises helped reinforce the relationship between Java objects and relational databases through ORM concepts.

---

## 📌 Resumo (Português)

Neste módulo estudei os fundamentos de JPA e Hibernate, aprendendo como funciona o mapeamento objeto-relacional (ORM) em aplicações Java.

Aprendi como transformar classes Java em entidades persistentes utilizando anotações como `@Entity`, `@Id` e `@GeneratedValue`, além de configurar o JPA através do arquivo `persistence.xml`.

Também conheci conceitos importantes como contexto de persistência, EntityManager, EntityManagerFactory e a integração com banco de dados MySQL.

Os exercícios focaram na criação de entidades e na persistência de objetos em banco de dados utilizando JPA e Hibernate, servindo como uma introdução prática ao acesso a dados em aplicações Java.
