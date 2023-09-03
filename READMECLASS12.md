# Reading Class 12

1- How are query methods defined when using Spring Data JPA?

- by extending from the repositry interface and by declaring their method signature. 

2- Which dependencies will you need in order to complete the Spring guide?

- Spring Boot Starter, Spring Web, Spring Data JPA , ThyMeleaf , Database driver and testing frameworks.

3- What annotations are used to specify an auto generated identification number for an Entity?

- @Id and @GeneratedValue in conjuction with @Id

4- Which of the Spring Data Repositories covered in the readings has the most methods available to it?

- Crud Repositry

5- Name a downstide of a Spring Data Repository.

- ReadOnlyRepository

6- How would you define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository?

- we can define a custom query method :  

```
public interface StudentRepository extends JpaRepository<Student, Long> {
   
    List<Student> findByName(String name);
}
```








