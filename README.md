# SpringDataRest
1.Created Spring Started Project with dependencies H2 Database, Rest Repositories, Spring Data JPA <br>
2.Used @GeneratedValue before id field annotation which will automatically generate id when we post data into database  before that added @Id annotation as well which makes Id as priamry key. <br>
3.Created Interface which extends JpaRepository<T, datatype> and used Annotation @RepositoryRestResource(collectionResourceRel = "aliens",path = "aliens") which helps in Crud operations. <br>
4.used PostMan for CRUD Operations.
