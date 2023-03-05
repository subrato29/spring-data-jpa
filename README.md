# spring-data-jpa

What is Spring Data JPA
---------------------------
```
Spring Data JPA(Java Persistence API) is not an implementation or JPA provider, it's just an 
abstraction on top of JPA to significantly reduce the amount of boilerplate code required to 
implement data access layers(DAO) for various persistence stores.

Spring Data JPA uses Hibernate as a default JPA provider. Spring Data JPA always requires a 
JPA provider such as Hibernate or Eclipse Link.

Spring Data JPA can not work without a JPA provider.

```

Difference between Hibernate and Spring Data JPA?
--------------------------
```
Hibernate is a JPA implementation, while Spring Data JPA is a JPA Data Access Abstraction. 
Spring Data offers a solution to GenericDao custom implementations.

```
