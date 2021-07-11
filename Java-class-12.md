# Spring Request Mapping

It is an annotation for mapping web requests.

We have five mapping methods (HTTP methods):

1. GetMapping

Annotated method handle the HTTP **GET** requests, which gets data from a specified API.

2. PostMapping

Annotated method handle the HTTP **POST** requests, which writes data to a specified API.

3. @PutMapping

Annotated method handle the HTTP **PUT** requests, which updates the data in a specified API.

4. @DeleteMapping

Annotated method handle the HTTP **DELETE** requests, which deletes specific data from a specified API.

5. @PatchMapping

Annotated method handle the HTTP **PATCH** requests, which updates a specific data in a specified API.

## Spring Data Repositories

1. CRUD repository

It provides the CRUD methods.

2. PagingAndSortingRepository

It provides additional methods to retrieve entities using pagination and sorting.

3. JpaRepository

It provides some JPA methods such as flushing the persistence context and deleting records in a batch.
