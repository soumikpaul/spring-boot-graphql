# spring-boot-graphql
Simple Spring Boot Application for understanding GraphQL

Example of Query:

{
    book(id: "123") {  
        title,
        authors  
    }
    allBooks {
        title //or any number of you want
    }
    
}
